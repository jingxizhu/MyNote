# Mysql 问题集

## 问题1：

```shell
ERROR 2002 (HY000): Can't connect to local MySQL server through socket '/var/lib/mysql/mysql.sock' (111)ERROR 2002 (HY000): Can't connect to local MySQL server through socket '/var/lib/mysql/mysql.sock' (111)
```

## 解决方法

重启Mysql即可

```shell
service mysqld start
```

