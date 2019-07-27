# 记录专门共计的那些ip


## 分析一段mongodb.log的日志

### ip 
> 来自 一份真实数据，做了部分脱敏处理

- 106.12.223.232 河北省保定市 百度，log中一共出现 520次
> 2019-xT20:53:56.678+0000 I NETWORK  [conn1408] received client metadata from 106.12.223.232:32802 conn1408: { driver: { name: "PyMongo", version: "3.7.2" }, os: { type: "Linux", name: "CentOS Linux 7.6.1810 Core", architecture: "x86_64", version: "3.10.0.514.26.2.el7.x86_64" }, platform: "CPython 2.7.14.final.0" }
- 106.12.223.231 河北省保定市 百度，log中一共出现 910次
> 2019-xT19:31:26.216+0000 I NETWORK  [conn7485] received client metadata from 106.12.223.231:52428 conn7485: { driver: { name: "PyMongo", version: "3.7.2" }, os: { type: "Linux", name: "CentOS Linux 7.6.1810 Core", architecture: "x86_64", version: "3.10.0.514.26.2.el7.x86_64" }, platform: "CPython 2.7.14.final.0" }
- 106.12.223.230 河北省保定市 百度，log中一共出现 1996次
> 2019-xT20:01:51.205+0000 I NETWORK  [conn11002] received client metadata from 106.12.223.230:47344 conn11002: { driver: { name: "PyMongo", version: "3.7.2" }, os: { type: "Linux", name: "CentOS Linux 7.6.1810 Core", architecture: "x86_64", version: "3.10.0.514.26.2.el7.x86_64" }, platform: "CPython 2.7.14.final.0" }
- 106.12.223.229 河北省保定市 百度，log中一共出现 2次
> 2019-xT20:15:46.205+0000 I NETWORK  [conn5756] Error receiving request from client: ProtocolError: recv(): message msgLen 671088768 is invalid. Min 16 Max: 48000000. Ending connection from 106.12.223.229:243 (connection id: 5756)
- 106.12.223.195  616
### 端口 

### 结论：
基本可断定，这沙雕就专门买百度云的服务器黑别人数据库的！！还连号，尼玛