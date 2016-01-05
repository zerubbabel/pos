How to Install

1. Create/locate a new MySQL database to install Open Source Point of Sale into
2. Unzip and upload the Open Source Point of Sale files to web server
3. Execute the file database/database.sql to create the tables needed
4-6. Modify OSPOS configuration files

Browse to  "C:\wamp\www\opensourcepos\application\config" and look for a file called "database.php.tmpl".  Rename this file "database.php" and then open it so you can edit it.

You'll want to change lines 52-54.

52: $db['default']['username'] = 'yourusername';
53: $db['default']['password'] = 'yourpassword';
54: $db['default']['database'] = 'yourdatabase';

7. Go to your Point of Sale install via the browser
8. LOGIN using default username and password

The default login information is:

Username: admin
Password: pointofsale