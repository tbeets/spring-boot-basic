# spring-boot-basic

Ye' olde basic Spring Boot (web) sample project.

From [Manning's Spring Boot in Action](https://www.manning.com/books/spring-boot-in-action)

## Usage

```bash
brew tap pivotal/tap; brew install spring-boot
spring init --dependencies web,data-jpa,h2,thymeleaf --build maven spring-boot-1
mvn clean; mvn package
java -jar spring-boot-1-0.0.1-SNAPSHOT.jar
mvn spring-boot:run (same as above)
mvn dependency:tree
```

Instantiates a web application with persistence harness and embedded Tomcat.

## Resources

* [Externalizing Spring Boot Configuration](http://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-external-config.html)
* [Blog demonstrating EnVar properties and a method to have a default](http://mrhaki.blogspot.com/2015/09/spring-sweets-setting-configuration.html)