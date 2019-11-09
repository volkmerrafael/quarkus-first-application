# quarkus-first-application
Minha primeira aplicação usando quarkus

# Prerequisites
* JDK 8 or 11+ installed with JAVA_HOME configured appropriately
* Apache Maven 3.5.3+
* Postgressql

# database
* Config database connection: application.properties
* Example:

```java
quarkus.datasource.url: jdbc:postgresql://localhost:5432/quarkus
quarkus.datasource.driver: org.postgresql.Driver
quarkus.datasource.username: postgres
quarkus.datasource.password: quarkus@123
```

# start project
```java
mvn clean package
mvn compile quarkus:dev
http://localhost:8080/home
```
