## Welcome to maven

maven出现的目的是为了统一管理Jar，统一开发规范。

maven->pom.xml->本地仓库|私服仓库|中央仓库(http://maven.aliyun.com/nexus/content/groups/public)

* 依赖管理，对Jar包管理；

* 项目构建，项目编码完成后，对项目进行编译、测试、打包、部署一系列操作都通过命令来实现的；


## maven基础知识

maven基础知识包括maven安装、maven配置、maven运行。

### maven安装教程
直接解压（解压路径不要有中文、空格）；

### maven配置教程
配置环境变量;配置本地仓库;配置中央仓库(http://maven.aliyun.com/nexus/content/groups/public);

### maven运行教程
编译 mvn compile;测试 mvn test;打包 mvn package;部署 mvn tomcat:run;


## nuxus私服基础知识

nexus私服基础知识包括nexus安装、上传Jar到nexus，下载Jar从nexus。

### nexus安装教程
管理员权限-bin目录;安装 nexus install;启动 nexus start;关闭 nexus stop;

### 上传Jar到nexus
私服地址，浏览器直接上传;

### 下载Jar从nexus
pom.xml;浏览器Jar URL下载;
