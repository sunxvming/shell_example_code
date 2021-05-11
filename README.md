# shell_example_code
记录一些shell脚本的示例代码


* autodeploy.sh
单台游戏服务器部署的脚本


* roleinfo2db.sh
将游戏的日志文件进行处理，然后插入到数据库中

* scan_fatal.sh
扫描游戏的打印日志文件，并按照错误发生的次数(fatal报错的次数)记录进行统计

* watch_dist.sh
监控磁盘使用情况，一旦超过某个阈值，则清理相关的日志文件和数据库中的数据


* scan_disc_and_send_mail.sh
监控磁盘空间一旦超过某个阈值则发邮件通知