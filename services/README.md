##  services
#### mysql redis rabbitmq 服务

#### 启动服务命令
```
docker-compose -f docker-compose-services.yml up -d
```
#### 停止服务命令
```
docker-compose -f docker-compose-services.yml down
```

#### 配置文件
```
.env --- 环境变量配置文件
```


#### tensorflow2 环境


### redis.conf 准备文件
```
curl -O http://download.redis.io/redis-stable/redis.conf
```