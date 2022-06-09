# BDD-with-Selenium-JBehave

This template consist of a BDD(Behavior-driven development) framework with Selenium. The BDD tool that we'll be using is JBehave, since JBehave is a pure Java framework and it is based upon JUnit itself, it is very much compatible with JAVA projects.

## ## Steps for Execution.

1. Clone the repository

`git clone https://github.com/knoldus/BDD-with-Selenium-JBehave.git`

2. Move into the directory and exeute this command with appropriate inputs for Web Driver and it's location.

`export DRIVER=<Your Driver name goes here, execute this command without '<>'>`

`export DRIVER_PATH=<Your Driver path goes here, execute this command without '<>'>`


3. To run the tests:

`mvn clean -Dtest=DemoTest test`

## Technologies used

**Programming Language** - JAVA, Gherkins

**Build tool** - Maven

**Automation tool** - Selenium WebDriver

**BDD Tool** - JBehave

**IDE** - Intellij

## Dependecies Used

**JBehave**
```
        <dependency>
            <groupId>org.jbehave</groupId>
            <artifactId>jbehave-core</artifactId>
            <version>4.1</version>
            <scope>test</scope>
        </dependency>
```

**Selenium**
```
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-java</artifactId>
            <version>4.0.0</version>
        </dependency>
```
**TypeSafe Config**

```
        <dependency>
            <groupId>com.typesafe</groupId>
            <artifactId>config</artifactId>
            <version>1.4.1</version>
        </dependency>
```

For a better understanding, please refer to the blog:-
https://blog.knoldus.com/jbehave-how-to-get-started/
