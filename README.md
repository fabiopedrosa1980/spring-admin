# Spring Boot Admin

## Monitorando os seus Microserviços

## Configuração

### application.properties
- spring.boot.admin.client.url=http://localhost:8080
- spring.boot.admin.client.instance.name=teste-leroy
- management.endpoints.web.exposure.include=*
- management.endpoint.health.show-details=always

### pom.xml
 <dependency>
    <groupId>de.codecentric</groupId>
    <artifactId>spring-boot-admin-starter-client</artifactId>
    <version>2.1.6</version>
</dependency>

## Documentação
https://codecentric.github.io/spring-boot-admin/current/
