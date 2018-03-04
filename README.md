## Docker-Composer 多容器协作构建LNMP开发环境

## 简介
这是一个 Docker 多容器间协作互连的例子, 使用容器包括 `nginx`, `mysql`, `php-fpm`, `redis`, `mongo`;
site目录为站点根, 其中使用了Laravel框架来做演示;

## 操作
1. 下载仓库
2. 切换到`docker-compose.yml`模板文件所在目录
3. 执行 `docker-compose up -d`
4. 本机配置host `127.0.0.1 www.laravel.com`
5. 测试访问 `www.laravel.com:8090`