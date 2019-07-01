# Error: Unable to Retrieve CacheManager from JNDI  

This is just a repository housing an example of a failing configuration.
It is intended to just be used to demonstrate an error and then a fix for that error.

## Setup
**Maven**: Download Maven from the [download website](https://maven.apache.org/download.cgi).

**WildFly** : Download WildFly 8.2.1 from the [download website](https://wildfly.org/downloads/).

Clone this project to your local machine.
In `pom.xml`, change the `jboss-home` value to the location where you stored your WildFly instance. 

Open a terminal and browse to the location where you stored this project.
Run `mvn clean install wildfly:run`.
Once the server has started, browse to `http://localhost:8080/test/`.