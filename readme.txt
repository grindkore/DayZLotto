DayZLotto is a simple vbscript designed to update the default load out record of Bliss hive DB.
This script will insert random load out string in to 'instance' table resulting 
in survivors spawning in with random inventory items. I wrote this script to support
Bliss hive schema .30 and above.

Setup:
No special setup is necessary for this script run. The Windows Scripting Host is native to all windows installations.
Simple place this script in to any folder and execute it using any batch file, command line, or simply double clicking it.
You will need to make sure you have MySQL ODBC connector installed on the machine that is running this script in order for it to
connect to the MySQL database. You can download ODBC drivers here http://dev.mysql.com/downloads/connector/odbc/

Instruction:
1) Modify DB connection parameters
2) Modify the loadout values if you want something different,
3) Use BEC scheduler or windows schedule to run this script
Notes: To add more loadouts simply add new dLoadout.Add "[inventry]","[backpack]". Also don't forget to use double "" to escape " character in VBS.
