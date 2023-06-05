# IM(即时通讯)

基于Golang、Websocket、MongoDB 实现即时通讯

# 技术栈

语言: Golang 数据库: MongoDB 框架: GIN 协议: Websocket

# 核心包

https://github.com/gorilla/websocket

# 扩展安装

```bash
go get -u github.com/gin-gonic/gin
go get github.com/gorilla/websocket
go get go.mongodb.org/mongo-driver/mongo
go get -u github.com/golang-jwt/jwt/v4
go get github.com/satori/go.uuid
```

# Docker 安装 mongoDB

```bash
docker run -d --network some-network --name some-mongo \
-e MONGO_INITDB_ROOT_USERNAME=admin \
-e MONGO_INITDB_ROOT_PASSWORD=admin \
-p 27017:27017 \
mongo
```
