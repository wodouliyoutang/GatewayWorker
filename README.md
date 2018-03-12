workerman-chat
=======
基于workerman的GatewayWorker框架开发的一款高性能支持分布式部署的聊天室系统。


 * 业务逻辑全部在一个文件中，快速入门可以参考这个文件[Applications/Chat/Event.php](https://github.com/walkor/workerman-chat-for-win/blob/master/Applications/Chat/Event.php)   
  * 本案例为win版，linux部署需要替换linux版的GatewayWorker类库包 

目录
====

----Application         开发应用项目
        
----vendor              GatewayWorker框架

----start_for_win.bat   运行脚本




安装部署
=====

下载 或者 clone 代码到本地

要求 php>=5.3.3 并且配置好了php环境变量
  
运行
=====
启动

双击  start_for_win.bat

停止

ctrl+c 停止


测试
=======
浏览器访问 http://服务器ip或域:55151,例如http://127.0.0.1:55151


默认心跳为服务器发送客户端,间隔10s

 [更多请访问http://blog.xiaolan222.xin]
