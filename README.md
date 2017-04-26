# Test for using Spring Boot, Spring Loaded and Vaadin

## Starting the project command line
---
```mvn install spring-boot:run```
and
open http://localhost:8080 in the browser

## Starting the project in an IDE
---
Option 1, launch ```spring-boot:run``` from your IDE

Option 2, launch the Application class, in this case you need to

1. Download springloaded.jar (e.g. from https://repo.spring.io/webapp/#/artifacts/browse/tree/General/libs-snapshot-local/org/springframework/springloaded/1.2.8.BUILD-SNAPSHOT). 
2. Add the JVM arguments ```-javaagent:/Users/foo/bar/springloaded.jar -noverify``` to your Application launch configuration

##### After starting the project, edit MyUI.java and make some changes. The browser will be updated automatically when you save
