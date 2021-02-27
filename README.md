# Demo application for Spring Boot Actuator

The purpose of the application is to help you in initial set up of spring boot actuator. It will help you in
1) Enable actuator in spring boot
2) Enable/disable any actuator endpoint
3) Customize some exisitng actuator endpoint

## Project details
Spring boot version: 2.4.2

Build tool: Maven

## Run the application
Build this project using command: ```mvn install```

You can run this application from your IDE as simple JAVA application. Or you can follow, [Run your application](https://docs.spring.io/spring-boot/docs/current/reference/html/using-spring-boot.html#using-boot-running-your-application)

This project will run on in-built tomcat server on default port: 8080

## Endpoint Details
By default, actuator endpoints are exposed over http via application port.

Base path: http://localhost:8080

1) To view list of actuator endpoints

   ```GET /actuator```

2) to view output of actuator endpoint

   ```GET /actuator/<endpoint>```

   e.g. ```/actuator/info```

3) View list of metrics

   ```GET /actuator/metrics```

4) View output of given metrics

   ```GET /actuator/metrics/<metric_name>```

   e.g. ```/actuator/metrics/process.uptime```



