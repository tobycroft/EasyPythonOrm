# EasyPythonOrm

EasyPythonOrm目前仅支持MySQL

Easy Python Orm is only support Mysql yet

# 新手用户

EasyPythonOrm可以让你像ThinkPHP或者Laraval那样使用Eloquent方式操作MySQL数据库

You can easily operate mysql by using Db().Table().where().find() to get your data.

# 安全性

基于pyMysql最新版，Database加入了prepare statement（PDO），避免老版本PYMYSQL可能导致的注入风险

And most importantly, this ORM support mysql PDO which will make each query much safer