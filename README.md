# PHP开发环境

## 制作目的

+ 受限国内网络环境，对于下载`pecl.php.net`与`gihub.com`这些站点上的包有些困难, 所以直接固化成基础包

## 镜像内容

### 基础镜像

+ 该镜像基于`php:7.1-fpm-alpine`

### 包含拓展

+ pdo_mysql 
+ mysqli 
+ bcmath 
+ opcache 
+ sockets 
+ pcntl 
+ calendar 
+ sysvmsg 
+ sysvsem 
+ sysvshm
+ gd
+ imagick
+ redis
+ memcached
+ mongodb
+ swoole

