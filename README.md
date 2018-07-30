# spring-boot-rest-example
spring boot restful example from 
Building a RESTful Web Service
https://spring.io/guides/gs/rest-service/

## to run : 
MAVEN command : ./mvnw spring-boot:run

## test :
1. visit http://localhost:8080/greeting
you should see 
{"id":1,"content":"Hello, World!"}
2. visit http://localhost:8080/greeting?name=[your_name]
you should see
{"id":1,"content":"Hello, your_name!"}
