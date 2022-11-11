To enable MySQL in XAMPP
1. Open Task Manager
2. Click on Services Tab
3. Look for MySQLD80 service
4. Right click "MySQLD80" service then select "Stop" to terminate the service
5. Open XAMPP Control Panel
6. You can click the "Start" button in line with the MySQL module and then wait for 3306 to be displayed.

Click "shell" to launch the XAMPP Command Prompt

To login use this command.
mysql -u root -p 

-u username
root default username provided by XAMPP
-p password
in XAMPP there is no password provided

To SHOW all databases, use this command
SHOW DATABASES;

To create databse, use this command
CREATE DATABASE databasename;

databasename can be any name, alphanumeric characters, underscores or dashes

To access the database, use this command
USE databasename;

To show information about a table, use this command
DESCRIBE tablename;
