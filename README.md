# MyClass-Gradle

## Run the init task:

```
$ gradle init

Select type of project to generate:
  1: basic
  2: cpp-application
  3: cpp-library
  4: groovy-application
  5: groovy-library
  6: java-application
  7: java-library
  8: kotlin-application
  9: kotlin-library
  10: scala-library
Enter selection (default: basic) [1..10] 6

Select build script DSL:
  1: groovy
  2: kotlin
Enter selection (default: groovy) [1..2] 

Select test framework:
  1: junit
  2: testng
  3: spock
Enter selection (default: junit) [1..3] 

Project name (default: MyClass-Gradle): 
Source package (default: MyClass.Gradle): my.zhamri.gradle

BUILD SUCCESSFUL in 1m 18s
2 actionable tasks: 2 executed
```

## Execute the build:

```
$ gradle build
```
You may also try 
```
$ ./gradlew build
``` 

## Run the app:

```
$ gradle run

> Task :run
Hello world.

BUILD SUCCESSFUL in 9s
2 actionable tasks: 1 executed, 1 up-to-date
```
You may also try 
```
$ ./gradlew run
``` 

## References:

1. https://guides.gradle.org/building-java-applications/
2. https://spring.io/guides/gs/gradle/
   