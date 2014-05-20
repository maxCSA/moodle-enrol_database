You must also add the following line to theses files:

moodle/lib/enrollib.php ( near the top of the file)
	define('ENROL_EXT_REMOVED_ALL', 0);
	define('ENROL_EXT_REMOVED_TABLE', 1);

moodle/lang/en/enrol.php ( at the end of the file )
	$string['extremovedscope'] = 'Unenrolment action scope';
	$string['extremovedscope_help'] = 'Define to which courses unenrol action should be applied';
	$string['extremovedtable'] = 'Unenrol for courses in external table only';
	$string['extremovedall'] = 'Unenrol for all courses';
