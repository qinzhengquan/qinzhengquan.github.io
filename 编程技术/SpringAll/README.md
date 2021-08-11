**版本说明**：

spring： 5.1.3.RELEASE

spring-boot：2.1.1.RELEASE

spring-cloud：Finchley.SR2
<br/>

>[大数据入门指南](https://github.com/heibaiying/BigData-Notes)

## 1. spring samples

所有 spring 的项目我都会提供两个版本的 sample：

- 一个版本是基于 xml 配置，也就是最为常见的配置方式；
- 另一个版本完全基于代码配置（项目以**annotation**结尾），这也是目前 spring 官方推荐的更为灵活配置方法，也方便更好的衔接 spring boot 的配置。

| samples                                                      | 描述                                                         | 官方文档                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [springmvc-base](编程技术/SpringAll/Spring/SpringMVC基础(基于XML配置).md)<br/>[springmvc-base-annotation](编程技术/SpringAll/Spring/SpringMVC基础(基于注解).md) | springmvc 基础、参数绑定、格式转换、数据校验、<br/>异常处理、 文件上传下载、视图渲染 | [Spring Mvc ](https://docs.spring.io/spring/docs/5.1.3.RELEASE/spring-framework-reference/web.html#mvc) |
| [spring-aop](Spring/SpringAOP(XML配置方式).md)<br/>[spring-aop-annotation](Spring/SpringAOP(注解方式).md) | spring 切面编程                                               | [Spring AOP](https://docs.spring.io/spring/docs/5.1.3.RELEASE/spring-framework-reference/core.html#aop) |
| [spring-jdbc](Spring/Spring整合JDBCTemplate(XML配置方式).md)<br/>[spring-jdbc-annotation](Spring/Spring整合JdbcTemplate(注解方式).md) | spring jdbc-template 的使用                                  | [Using JdbcTemplate](https://docs.spring.io/spring/docs/5.1.3.RELEASE/spring-framework-reference/data-access.html#jdbc-JdbcTemplate) |
| [spring-mybatis](Spring/Spring整合Mybatis(XML配置方式).md)<br/>[spring-mybatis-annotation](Spring/Spring整合Mybatis(注解方式).md) | spring 整合 mybatis                                          | [Mybatis-Spring](http://www.mybatis.org/spring/zh/index.html) |
| [spring-druid-mybatis](Spring/Spring+Druid+Mybatis(XML配置方式).md)<br/>[spring-druid-mybatis-annotation](Spring/Spring+Druid+Mybatis(注解方式).md) | spring 整合 druid、mybatis                                    | [Alibaba druid](https://github.com/alibaba/druid/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98) |
| [spring-redis](Spring/Spring整合Redis(XML配置方式).md)<br/>[spring-redis-annotation](Spring/Spring整合Redis(注解方式).md) | spring 整合 redis 单机 + 集群（jedis 客户端）<br/>spring 整合 redis 单机 + 集群（redisson 客户端） | [Redisson](https://github.com/redisson/redisson/wiki/%E7%9B%AE%E5%BD%95) |
| [spring-mongodb](Spring/Spring整合MongoDB(XML配置方式).md)<br/>[spring-mongodb-annotation](Spring/Spring整合MongoDB(注解方式).md) | spring 整合 mongodb                                          | [Spring Data MongoDB](https://docs.spring.io/spring-data/mongodb/docs/2.1.3.RELEASE/reference/html/#mongo.mongo-db-factory-java) |
| [spring-memcached](Spring/Spring整合Mecached(XML配置方式).md)<br/>[spring-memcached-annotation](Spring/Spring整合Mecached(注解方式).md) | spring 整合 memcached(单机 + 集群)                             | [Xmemcached](https://github.com/killme2008/xmemcached/wiki/Xmemcached%20%E4%B8%AD%E6%96%87%E7%94%A8%E6%88%B7%E6%8C%87%E5%8D%97) |
| [spring-rabbitmq](Spring/Spring整合RabbitMQ(XML配置方式).md)<br/>[spring-rabbitmq-annotation](Spring/Spring整合RabbitMQ(注解方式).md) | spring 整合 rabbitmq、消息序列化与反序列化                   | [Rabbitmq](http://www.rabbitmq.com/getstarted.html)<br>[Spring AMQP](https://docs.spring.io/spring-amqp/docs/2.1.3.BUILD-SNAPSHOT/reference/html/) |
| [spring-dubbo](Spring/Spring整合Dubbo(XML配置方式).md)<br/>[spring-dubbo-annotation](Spring/Spring整合Dubbo(注解方式).md) | spring 整合 dubbo                                            | [Dubbo ](http://dubbo.apache.org/zh-cn/docs/user/quick-start.html) |
| [spring-websocket](Spring/SpringWebSocket(XML配置方式).md)<br/>[spring-websocket-annotation](Spring/SpringWebSocket(注解方式).md) | spring 整合 websocket                                        | [Spring Websocket](https://docs.spring.io/spring/docs/5.1.3.RELEASE/spring-framework-reference/web.html#websocket) |
| [spring-mail](Spring/Spring邮件发送(XML配置方式).md) <br/>[spring-mail-annotation](Spring/Spring邮件发送(注解方式).md) | spring 普通文本邮件、附件邮件、模板邮件                      | [Spring Email](https://docs.spring.io/spring/docs/5.1.3.RELEASE/spring-framework-reference/integration.html#mail) |
| [spring-scheduling](Spring/Spring定时任务(XML配置方式).md)<br/>[spring-scheduling-annotation](Spring/Spring定时任务(注解方式).md) | spring 定时任务                                              | [Task Execution and Scheduling](https://docs.spring.io/spring/docs/5.1.3.RELEASE/spring-framework-reference/integration.html#scheduling) |

<br/>

## 2. spring-boot samples

| samples                                                      | 描述                                       | 官方文档                                                     |
| ------------------------------------------------------------ | ------------------------------------------ | ------------------------------------------------------------ |
| [spring-boot-base](SpringBoot/SpringBoot基础.md) | spring-boot 基础                           | [spring boot 官方文档](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/)<br>[spring boot 中文官方文档](https://www.breakyizhan.com/springboot/3028.html) |
| [spring-boot-yml-profile](SpringBoot/SpringBoot-YAML.md) | yml 语法和多配置切换                       | [Using YAML Instead of Properties](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#boot-features-external-config-yaml) |
| [spring-boot-tomcat](SpringBoot/SpringBoot整合Tomcat.md) | spring-boot 整合外部容器（tomcat）         | [Use Another Web Server](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#howto-use-another-web-server) |
| [spring-boot-servlet](SpringBoot/SpringBoot整合Servlet.md) | spring boot 整合 servlet 3.0                | [Embedded Servlet Container Support](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#boot-features-embedded-container) |
| [spring-boot-jsp](SpringBoot/SpringBoot整合JSP.md) | spring-boot 整合 jsp（内置容器）           | [JSP Limitations](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#boot-features-jsp-limitations) |
| [spring-boot-data-jpa](SpringBoot/SpringBoot-Data-JPA.md) | spring-boot data jpa 的使用                | [Spring Data JPA](https://docs.spring.io/spring-data/jpa/docs/2.1.3.RELEASE/reference/html/) |
| [spring-boot-mybatis](SpringBoot/SpringBoot整合Mybatis.md) | spring-boot+HikariDataSources 整合 mybatis | [Mybatis-Spring](http://www.mybatis.org/spring/zh/index.html)<br/>[Mybatis-Spring-Boot-Autoconfigure](http://www.mybatis.org/spring-boot-starter/mybatis-spring-boot-autoconfigure/) |
| [spring-boot-druid-mybtais](SpringBoot/SpringBoot整合Druid+Mybatis.md) | spring-boot 整合 druid、mybatis             | [Alibaba druid](https://github.com/alibaba/druid/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)<br/>[druid-spring-boot-starter](https://github.com/alibaba/druid/tree/master/druid-spring-boot-starter) |
| [spring-boot-redis](SpringBoot/SpringBoot整合Redis.md) | spring-boot 整合 redis                     | [Working with NoSQL Technologies](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#boot-features-nosql) |
| [spring-boot-mongodb](SpringBoot/SpringBoot整合MongoDB.md) | spring-boot 整合 mongodb                   | [Working with NoSQL Technologies](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#boot-features-nosql) |
| [spring-boot-memcached](SpringBoot/SpringBoot整合Memcached.md) | spring-boot 整合 memcached                 | [Xmemcached](https://github.com/killme2008/xmemcached/wiki/Xmemcached%20%E4%B8%AD%E6%96%87%E7%94%A8%E6%88%B7%E6%8C%87%E5%8D%97) |
| [spring-boot-rabbitmq](SpringBoot/SpringBoot整合RabbitMQ.md) | spring-boot 整合 rabbitmq                  | [RabbitMQ support](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#boot-features-rabbitmq) |
| [spring-boot-dubbo](SpringBoot/SpringBoot整合Dubbo.md) | spring-boot 整合 dubbo                     | [Dubbo ](http://dubbo.apache.org/zh-cn/docs/user/quick-start.html) |
| [spring-boot-websocket](SpringBoot/SpringBoot整合WebSocket.md) | spring-boot 整合 websocket                 | [Using @ServerEndpoint](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#howto-create-websocket-endpoints-using-serverendpoint) |
| [spring-boot-kafka](SpringBoot/SpringBoot整合Kafka.md) | spring-boot 整合 kafka                     | [Apache Kafka Support](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#boot-features-kafka) |
| [spring-boot-actuator](SpringBoot/SpringBoot-Actuator.md) | actuator + Hyperic SIGAR 应用信息监控      | [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/2.1.1.RELEASE/reference/htmlsingle/#production-ready) |
| [spring-boot-swagger2](SpringBoot/SpringBoot集成Swagger2.md) | spring-boot 集成 Swagger2 打造在线接口文档 | [Springfox Reference Documentation](http://springfox.github.io/springfox/docs/current/) |

<br/>

## 3. spring-cloud  samples

| samples                                                      | 描述                                                         | 官方文档                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [spring-cloud-Eureka](SpringCloud/Eureka服务的注册与发现.md) | Eureka 服务的注册和发现                                      | [Service Discovery: Eureka Server](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi_spring-cloud-eureka-server.html) |
| [spring-cloud-Eureka-cluster](SpringCloud/Eureka高可用注册中心的搭建.md) | Eureka 高可用集群搭建                                        | [Service Discovery: Eureka Server](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi_spring-cloud-eureka-server.html) |
| [spring-cloud-Ribbon](SpringCloud/Spring-Cloud-Ribbon.md) | Ribbon 客户端负载均衡<br/>RestTemplate 服务远程调用          | [Client Side Load Balancer: Ribbon](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi_spring-cloud-ribbon.html) |
| [spring-cloud-OpenFeign](SpringCloud/Spring-Cloud-Feign.md) | OpenFeign 声明式服务调用、服务容错处理                       | [Declarative REST Client: Feign](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi_spring-cloud-feign.html) |
| [spring-cloud-Hystrix](SpringCloud/Spring-Cloud-Hystrix-Turbine.md) | Hystix 服务容错保护<br/>hystrix dashboard 断路器监控<br>Turbine 断路器聚合监控 | [Circuit Breaker: Hystrix Clients](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi__circuit_breaker_hystrix_clients.html)<br/>[Hystrix metrics aggregation with Turbine](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi_spring-cloud-consul-turbine.html) |
| [spring-cloud-Zuul](SpringCloud/Spring-Cloud-Zuul.md) | Zuul 网关服务                                                | [Router and Filter: Zuul](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi__router_and_filter_zuul.html) |
| [spring-cloud-Sleuth-Zipkin](SpringCloud/Spring-Sleuth-Zipkin.md) | Sleuth + Zipkin 服务链路追踪                                 | [Spring Cloud Sleuth](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi__introduction.html#sleuth-adding-project) |
| [spring-cloud-Config-Bus](SpringCloud/Spring-Cloud-Config.md) | Config 分布式配置中心 <br>集成 Bus 消息总线 实现配置热更新     | [Spring Cloud Config Client](https://cloud.spring.io/spring-cloud-static/Finchley.SR2/multi/multi__spring_cloud_config_client.html) |

<br/>

## 4.spring分布式session和分布式事务

| sample                                                       | 描述                                                         | 官方文档                                                     |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [spring-session](SpringSession/Spring实现分布式Session.md) | spring 实现分布式 session                                    | [spring session](https://spring.io/projects/spring-session#learn) |
| [spring boot + spring session](SpringSession/SpringBoot实现分布式Session.md) | spring boot + spring session 实现分布式 session              | [spring session](https://spring.io/projects/spring-session#learn) |
| [springboot-druid-mybatis-atomikos](SpringBoot/SpringBoot+Druid+Mybatis+Atomikos.md) | spring boot + druid + mybatis + atomikos<BR> 配置多数据源、支持分布式事务 ( JTA 方式实现) | [Distributed Transactions with JTA](https://docs.spring.io/spring-boot/docs/2.1.2.RELEASE/reference/htmlsingle/#boot-features-jta) |

<br/>
