# todo_example_web.py
https://github.com/webpy/webpy.github.com/blob/master/src/todo-list/0.3.md
web.py example of a simple todo project


#1. --Mac 上安装及配置mysql
brew install mysql
brew services start mysql (启动)

#2. 虚拟环境中安装下面的包
-虚拟环境python 3.6.4
pip install web.py==0.40.dev0 
pip install mysqlclient

#3. 在Mac 上创建数据库，名字todo
#4. 执行schema.sql 去创建表

#5. 启动web 应用：
http://0.0.0.0:8080/

6. 查看数据库
mysql> select * from todo;
+----+-----------------+
| id | title           |
+----+-----------------+
|  1 | write test case |
|  2 | 读书            |
|  3 | 学习python      |
|  4 | 打网球          |
+----+-----------------+
4 rows in set (0.00 sec)
