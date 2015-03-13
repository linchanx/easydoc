本项目采用php开发，是我为我公司开发的一个超简单的文档管理系统，主要实现了文件转发、短消息、上传文件、发送通知这些功能。

本系统需要将php.ini文件里面的post\_max\_size 值设为50m，output\_buffering设为on，windows用户需要修改session.save\_path目录。

由于是为公司开发的系统，所以没有做数据库安装程序，请在mysql中创建eoffice数据库然后执行 mysql eoffice<eoffice.sql。

请使用root账号密码root@123 登录系统，里面有创建用户的功能。

http://eoffice-linchanx.dotcloud.com/