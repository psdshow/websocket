# websocket
一个 PHP 的 websocket 的聊天室

具体设计可查看：[网页实时聊天之PHP实现websocket](http://www.cnblogs.com/zhenbianshu/p/6111257.html)


开启
extension=php_gd2.dll
extension=php_sockets.dll

另外windows下使用时 
server.php里面的posix_getpid 替换成 get_current_user
