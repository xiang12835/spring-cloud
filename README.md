# Spring Cloud

## Build Setup

- 打开pom.xml
- 运行数据库
- 运行 ApiApplication
- 浏览器打开 http://localhost:9000/swagger-ui.html

## 内容

>服务通信

- 服务访问：Feign（RESTful 通信）
- 负载均衡：Ribbon（实现服务间稳定通信）

>服务网关

- Spring Cloud Gateway
- [SpringCloud gateway （史上最全）](https://www.cnblogs.com/crazymakercircle/p/11704077.html)


>服务治理

- Eureka

>服务容错

- 超时
- 熔断：Hystrix
- 隔离
- 限流：GateWay + Redis（分布式），Guava（单机）
- 降级
- 重试：网关的过滤器实现

>服务调度

- [Spring Boot(九)：定时任务](http://www.ityouknow.com/springboot/2016/12/02/spring-boot-scheduler.html)

## 项目介绍

>common

公共

>office

智能办公、知识库

>gateway

网关工程

>registry

服务注册与发现

>scheduler

定时任务