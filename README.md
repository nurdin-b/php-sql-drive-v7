# php-sql-drive-v7
Microsoft Drivers for PHP for SQL Server, using white php v.7.3.33

##  Installation Steps:
1.  Download Microsoft Drivers for PHP for SQL Server:
-  Visit the official Microsoft Drivers for PHP for SQL Server download page.
-  Choose the appropriate version of the driver for your PHP version (in your case, PHP 7.3).
-  Download the driver package (usually in a .zip or .dll format) to your computer.

2.  Unzip Files:
-  Extract the contents of the downloaded driver package to a temporary location on your computer.

3.  Open the php-sql-drive-7 Directory:
-  Navigate to the directory where you extracted the driver files.

4.  Copy All Files:
-  Select all the files contained in the php-sql-drive-7 directory.

5.  Paste the Files in Your PHP Extension Directory:
-  Locate the PHP extension directory in your XAMPP installation. The path is typically xampp\php\ext.
-  Paste the files you copied from the php-sql-drive-7 directory into the PHP extension directory.

6.  Configure PHP to Use the SQL Server Driver:
-  Open your php.ini file, which is typically located in xampp\php\php.ini.
follow this code:
extension=php_sqlsrv_73_ts_x64.dll
extension=php_pdo_sqlsrv_73_ts_x64.dll
-  Save the php.ini file.
7.  Restart Apache
Restart the Apache server in XAMPP to apply the changes.

That's it! You should now have Microsoft Drivers for PHP for SQL Server installed and configured in your XAMPP environment. Make sure to check for any updates or changes in the installation process if you encounter any issues.
