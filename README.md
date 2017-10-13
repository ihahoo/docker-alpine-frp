# docker-alpine-frp
frp在alpine下制作的docker镜像，镜像大小不到20M

当前frp版本0.13.0

## 服务器端
服务器端安装好docker和docker-compose环境

登录服务器，将[server/](https://github.com/ihahoo/docker-alpine-frp/tree/master/server)下的文件下载到服务器某目录中

修改`frps.ini`配置文件，然后通过docker-compose启动
```
$ docker-compose up -d
```
在主机当前目录中，frps.log为日志文件


