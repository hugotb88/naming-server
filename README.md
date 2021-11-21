# naming-server
Eureka Naming Server project for UDEMY Microservices Rest course

# Initial Structure of the project
![image](https://user-images.githubusercontent.com/36638342/142776562-26b22ece-0f81-405c-9377-7317ddb18d6d.png)

# Ports
![img.png](img.png)

# How to Register a microservice in Eureka
- in the POM of the microservice project add the dependency for Eureka client
```
    <dependency>
        <groupId>org.springframework.cloud</groupId>
        <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
    </dependency>
```
Additional, just to be sure, you can add the following to the properties file
``eureka.client.serviceUrl.defaultZone = http://localhost:8761/eureka``

Before Add the depdendency in the microservices projects
![img_1.png](img_1.png)

After...
![img_2.png](img_2.png)
