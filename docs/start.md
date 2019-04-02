

开始
===

### 创建新的项目，app-test这项目名称
bee api app-test

```$xslt
       create src/app-test
       create src/app-test/main.go
       create src/app-test/conf
       create src/app-test/controllers
       create src/app-test/tests
       create src/app-test/conf/app.conf
       create src/app-test/models
       create src/app-test/routers/
       create src/app-test/routers/router.go
       create src/app-test/controllers/object.go
       create src/app-test/controllers/user.go
       create src/app-test/tests/default_test.go
       create src/app-test/models/object/model.go
       create src/app-test/models/user/model.go
       create src/app-test/pkg/middle-wares/middleware.go
       create src/app-test/pkg/middle-wares/allow-all.go
       create src/app-test/pkg/middle-wares/allow-token.go
       create src/app-test/service-logics/user/user.go
       create src/app-test/service-logics/health-checks/database.go
       create src/app-test/service-logics/health-checks/redis.go
```

### 项目基本目录结构说明



| /main.go                                      | 入口文件                   |           
| /conf                                         | 配置目录                   |           
| /conf/app.conf                                |                           |        
| /tests                                        | 测试代码                   |           
| /tests/default_test.go                        |                           |        
| /routers/                                     | 路由层                     |          
| /routers/router.go                            |                           |        
| /controllers                                  | 控制器层                   |           
| /controllers/object.go                        |                           |        
| /controllers/user.go                          |                           |        
| /models                                       | 模型层                     |          
| /models/object/model.go                       |                           |        
| /models/user/model.go                         |                           |        
| /pkg/middle-wares/middleware.go               | 中间件                     |          
| /pkg/middle-wares/allow-all.go                | 开放访问的请求配置           |              
| /pkg/middle-wares/allow-token.go              | 登录用户即可访问的请求配置    |                 
| /service-logics                               | 服务层                     |          
| /service-logics/user/user.go                  |                           |        
| /service-logics/health-checks                 | 健康检察验证器              |             
| /service-logics/health-checks/database.go     | 数据库连接检查              |             
| /service-logics/health-checks/redis.go        | redis连接检查              |           
                                                 