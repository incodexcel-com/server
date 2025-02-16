# server


mysql> CREATE USER 'admin'@'%' IDENTIFIED BY 'Qwer!1234';
mysql> GRANT ALL PRIVILEGES ON *.* TO 'admin'@'%' WITH GRANT OPTION;
mysql> FLUSH PRIVILEGES;
