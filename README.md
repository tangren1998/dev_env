# 本地开发环境（单机）
## docker compose
- db：mongodb
- cache：redis  
mongo-express：mongodb 的 web 客户端
## 通过的测试环境
- win10

# 命令
## docker-compose 常用命令
- docker-compose up [-d] （创建并运行）
- docker-compose down （停止并移除）

## docker 常用命令
- docker network ls
- docker image ls
- docker container ls   （查看正在运行的容器）
- docker exec -it <container-name> bash （使用容器名登录容器）

## mongodb 常用命令
- mongo -u <username> -p <password> [--authenticationDatabase <database-name>]