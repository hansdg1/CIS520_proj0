Adding another test (alarm-mega) to perform 70 alarms

Browse to pintos/src/tests/threads
	- cp alarm-multiple.ck alarm-mega.ck
	- edit alarm-mega.ck
		- change 'check_alarm (7);' to 'check_alarm (70);'
Browse to pintos/src/threads
	- Run the following commands to find all parts of the 'alarm-multiple' test program. Then create appropriate ones for 'alarm-mega'
		- grep -nri alarm-multiple *
		- grep -nri alarm_multiple *

Lastly, run make clean
