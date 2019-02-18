### Spring boot相关知识点

1.项目的健康检查,beans

```
1.1 引入依赖
<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
		</dependency>
1.2 beans查看 在application.properties中引入
management.endpoints.web.exposure.include=*

1.3查看所有的beans
http://localhost:8080/actuator/beans
健康：http://localhost:8080/actuator/health
```



