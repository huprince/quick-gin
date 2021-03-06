# quick-gin
基于gin 框架的 Go 语言 RESTFul API 开发脚手架 

## 基础组件集成

1. [x] 基础 WEB 框架: [gin](https://github.com/gin-gonic/gin)
2. [x] 日志服务组件: 
   1. [x] [zap](https://github.com/uber-go/zap)
   2. [x] [lumberjack](https://github.com/natefinch/lumberjack)
3. [x] 环境配置组件: [godotenv](https://github.com/joho/godotenv)
4. [ ] 数据驱动组件
   1. [x] MySQL
   2. [ ] PostgreSQL
   3. [ ] Oracle
   4. [ ] MSSQL
   5. [ ] MongoDB
   6. [ ] ES
5. [x] ORM 组件、数据库迁移
6. [ ] 文件系统服务组件
7. [ ] Auth 认证组件
   1. [ ] session / cookie
   2. [ ] oauth 2.0 / jwt
8. [ ] 消息队列服务组件
   1. [ ] Redis
   2. [ ] kafka
   3. [ ] Memcached
9.  [ ] 前端模板引擎组件

## 自开发服务模块
1. [ ] 后台审计模块
2. [ ] 后台监控模块

## 第三方服务集成
1. [ ] 微信开发
   1. [ ] 公众号（订阅号、服务号）
   2. [ ] 企业微信
   3. [ ] 微信小程序
2. [ ] 第三方企业应用开发
   1. [ ] 阿里钉钉开发
   2. [ ] 字节飞书开发
3. [ ] 支付服务开发
   1. [ ] 微信支付
   2. [ ] 支付宝支付
4. [ ] 消息推送服务开发
   1. [ ] 邮件发送服务
   2. [ ] 短信发送平台
   3. [ ] 第三方应用消息推送平台
      1. [ ] 极光推送
      2. [ ] 小米推送
5. [ ] 对象存储服务
   1. [ ] 腾讯OSS
   2. [ ] 阿里OSS
   3. [ ] 七牛OSS

## 参考资料
1. [https://github.com/yinggaozhen/awesome-go-cn](https://github.com/yinggaozhen/awesome-go-cn)
2. [https://github.com/chenhg5/morningo](https://github.com/chenhg5/morningo)
3. [golang zap 日志使用](https://segmentfault.com/a/1190000023321533)