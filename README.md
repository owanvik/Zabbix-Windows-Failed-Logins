# Zabbix-Windows-Failed-Logins

Zabbix template to monitor Failed logins on a Windows Server.

Installation:
1. Import template
2. Add template to host

This template looks for the failed login event in the event log and fires a trigger if someone has a failed login.
There is a regex query getting the username, domain and workstation name, adding it to the trigger info.
