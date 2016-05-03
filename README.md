# MySQL-MongoDB
- Mysql database scripts and applicaitons
- MongoDB
- HBase
- Hive
- Oracle PL/SQL

## Create recommendation service for BecomeBeauty website
- recommendation algorithm based on customers' purchase history and habits
- using Scala and MySQL

### MySQL 
- Start
$mysqld stop
$mysql.server start
It must show "SUCCESS!". To connect to mysql, using this for first time login.

- Login
$mysql -u root

- Create Database

```sql 
mysql> CREATE DATABASE menagerie;

mysql> USE menagerie

Database changed


mysql>CREATE TABLE pet (name VARCHAR(20), owner VARCHAR(20),
    -> species VARCHAR(20), sex CHAR(1), birth DATE, death DATE);
```

###MongoDB


###Reference 
[Start MySQL in Mac OS X](http://stackoverflow.com/questions/4788381/getting-cant-connect-through-socket-tmp-mysql-when-installing-mysql-on-m)