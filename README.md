1. Download the Project code and unzip into the /var/www/html
2. Connect to the DB and create database as mentioned in reference text file in code folder.
3. run the command in the server to import the tables and data from test.sql to database tables.
   mysql -h mysqldb.cl00o48m41xv.us-east-1.rds.amazonaws.com -u admin -p library < library.sql
4. After the import is successfull verify by connecting to DB and use Database as created above and check tables data.
5. After that go to the include folder in home path and also in admin path. Enter your DB endpoint and username and password and db.
