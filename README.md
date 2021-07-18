# Servlet Filter Sample Application
(https://github.com/iamshefaliarora/servlet-filter)

## Understanding the Spring filter application

## Running application locally
Servlet Filter is a [Spring Boot](https://spring.io/guides/gs/spring-boot) application built using [Maven](https://spring.io/guides/gs/maven/). You can run it from Maven directly using the Spring Boot Maven plugin. If you do this it will pick up changes that you make in the project immediately (changes to Java source files require a compile as well - most people use an IDE for this):


```
git clone https://github.com/iamshefaliarora/servlet-filter.git
cd servlet-filter
mvn spring-boot:run
```

You can then access application here: http://localhost:8080/

<img width="1042" alt="petclinic-screenshot" src="https://cloud.githubusercontent.com/assets/838318/19727082/2aee6d6c-9b8e-11e6-81fe-e889a5ddfded.png">

> NOTE: Windows users should set `git config core.autocrlf true` to avoid format assertions failing the build (use `--global` to set that flag globally).

## In case you find a bug/suggested improvement for Spring Servlet-Filter
Our issue tracker is available here: https://github.com/iamshefaliarora/servlet-filter/issues

## Working with Servlet-Filter in your IDE

### Prerequisites
The following items should be installed in your system:
* Java 8 or newer (full JDK not a JRE).
* git command line tool (https://help.github.com/articles/set-up-git)
* Your preferred IDE 
  * Eclipse with the m2e plugin. Note: when m2e is available, there is an m2 icon in `Help -> About` dialog. If m2e is
  not there, just follow the install process here: https://www.eclipse.org/m2e/
  * [Spring Tools Suite](https://spring.io/tools) (STS)

### Steps:

1) On the command line

    git clone https://github.com/iamshefaliarora/servlet-filter.git
    
2) Inside Eclipse or STS

    File -> Import -> Maven -> Existing Maven project

    Then either build on the command line `./mvnw generate-resources` or using the Eclipse launcher (right click on project and `Run As -> Maven install`) to generate the css. Run the application main method by right clicking on it and choosing `Run As -> Java Application`.

3) Navigate to Servlet-Filter

    Visit [http://localhost:8080](http://localhost:8080) in your browser.
