ECSE 437 Lab 3 Part 1

# A Java HelloWorld example
A "Hello World!" sample written in Java.

This example demonstrates:

* A simple Java 11 application with tests
* Unit tests written with [JUnit](https://junit.org/junit5/)
* Integration tests written with [JUnit](https://junit.org/junit5/)
* A [Maven](http://maven.apache.org/) build that puts it all together 

# Running the tests
* To run the unit tests, call `mvn test`
* To run the integration tests as well, call `mvn verify`

## Conventions

This example follows the following basic conventions:

| | unit test | integration test |
| --- | --- | --- |
| **resides in:** | `src/test/java/*Test.java` | `src/test/java/*IT.java` |
| **executes in Maven phase:** | test | verify |
| **handled by Maven plugin:** | [surefire](http://maven.apache.org/surefire/maven-surefire-plugin/) | [failsafe](http://maven.apache.org/surefire/maven-failsafe-plugin/) |
