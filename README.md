# socket-cluster-examples

# demo快速开始
- 依赖服务
    - redis
    - mysql
- 环境变量配置
```
#mysql
export DBDEFAULT_DBHOST="127.0.0.1"
export DBDEFAULT_DBNAME="socket_cluster"
export DBDEFAULT_DBUSER="root"
export DBDEFAULT_DBPASSWD=""

#redis
export REDIS_HOST="127.0.0.1:6379"
export REDIS_PASSWORD=""

#config
export RUN_TIME="local"
export EMAIL_PASSWORD=""
```
- 启动命令
```
cd github.com/weblazy/socket-cluster-examples/main/
./main
```