# MyQuarkus
一个Quarkus的示例工程，初步的想法是建立一个简单的Http WEB服务器，要包含ORM、数据库、日志等必备功能。
远期的想法是使用Quarkus搭建一个Native的R分布式微服务工程。
## 2023-01-06
在windows环境搞了挺久还是没有编译为本地镜像成功，最后在mint环境编译成功了。

基本就是下载GraalVM，设置JDK，执行linux环境的编译命令，最终成功编译。

需要安装好gcc，g++这些，然后安装开发工具库。
```shell
sudo apt-get install build-essential libz-dev zlib1g-dev
```
其他的问题就是参考GraalVM官网了。

所以说开发者要是有MacBook啊！

