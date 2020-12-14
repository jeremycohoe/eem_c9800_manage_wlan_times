Example EEM Applet that adjusts for DST changes to enable or disable the WLAN using the wireless profile feature

```
event manager applet Start_Of_DST
 event timer cron name DST_Start cron-entry "01 3 8-14 3 *"
 action 1.0 cli command "enable"
 action 2.0 cli command "show clock"
 action 2.1 syslog msg "$_cli_result"
 action 3.0 regexp "Sun" "$_cli_result"
 action 3.1 syslog msg "$_regexp_result"
 action 4.0 if $_regexp_result eq "1"
 action 4.1 syslog msg "End of Daylight Savings. Changing times for the following time zones: HST"
 action 4.2 syslog msg "Starting HST Calendar Profile - Adjusting for Pacific Time w/ DST - 3 Hours Ahead"
 action 4.3 cli command "configure terminal"
 action 4.4 cli command "wireless profile calender-profile name Hawaii_Workdays_8am_to_5pm"
 action 4.5 cli command "start 10:50:00 end 20:10:00"
 action 4.6 cli command "end"
 action 4.7 syslog msg "Finished HST Calendar Profile"
 action 4.8 end
 action 5 syslog msg "Finished all time zones."
```
