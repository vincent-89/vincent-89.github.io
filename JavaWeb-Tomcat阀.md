@[toc]



# 前言

`Filter`的功能之一就是预处理客户请求,而`Tomcat`阀是对`Catalina`容器接收到的`HTTP`请求进行预处理.

过滤器实在`Servlet`规范中提出来的,因此适用于所有的`Servlet`容器,而`Tomcat`阀是`Tomcat`转悠的,不能用于`Tomcat`以外的其他`Servlet`容器.



# 简介

阀可以加入到3种容器中:`<Engine>`/`<Host>`和`<Context>`.

所有的阀都实现了

