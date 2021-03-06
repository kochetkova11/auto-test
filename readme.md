# AutoTest Sample Application 
Тестирование ПО. Отчет.

> [Исходный текст задания](https://docs.google.com/document/d/18RBW8t4CCcIbdA06BKXMiwAmZx_uo7NBzxrFl8PQ90s/)


<img alt="Java" src="https://img.shields.io/badge/java-%23ED8B00.svg?&style=for-the-badge&logo=java&logoColor=white"/>
<img alt="Spring" src="https://img.shields.io/badge/spring%20-%236DB33F.svg?&style=for-the-badge&logo=spring&logoColor=white"/>
<img alt="Git" src="https://img.shields.io/badge/git%20-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white"/>
<img alt="LaTeX" src="https://img.shields.io/badge/latex%20-%23008080.svg?&style=for-the-badge&logo=latex&logoColor=white"/>


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/)

[![JDK](https://img.shields.io/badge/jdk-1.8.0-orange)](https://www.oracle.com/java/technologies/javase/8u271-relnotes.html)
[![ChromeDriver](https://img.shields.io/badge/chromedriver-87.0.4280.88-brightgreen)](https://chromedriver.storage.googleapis.com/index.html?path=87.0.4280.88/)
[![Selenium WebDriver](https://img.shields.io/badge/seleniumchromedriver-2.53.1-brightgreen)](https://www.javadoc.io/doc/org.seleniumhq.selenium/selenium-chrome-driver/2.53.1/org/openqa/selenium/chrome/ChromeDriver.html)
[![Maven](https://img.shields.io/badge/maven-3.6.3-blue)](https://maven.apache.org/docs/3.6.3/release-notes.html)
[![MavenCompiler](https://img.shields.io/badge/mavencompiler-3.5.1-blue)](https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-compiler-plugin/3.5.1)
[![MavenSurefire](https://img.shields.io/badge/mavensurefire-2.22.2-blue)](https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-surefire-plugin/2.22.2)
[![Junit](https://img.shields.io/badge/junit-4.12-red)](https://mvnrepository.com/artifact/junit/junit/4.12)
[![Allure](https://img.shields.io/badge/allure-2.10.0-blueviolet)]()

____

# Abstract
1. [Task 1](#task-1)
2. [Task 2](#task-2)
   1. [Task 2.1](#task-21)
   2. [Task 2.2](#task-22)
   3. [Task 2.3](#task-23)
   4. [Run Project](#run-project)
   5. [Allure Report](#allure-report)
      1. [Report](#report)
      2. [Suites](#suites)
      3. [Graphs](#graphs)
      4. [Timeline](#timeline)
3. [Technologies](#technologies)   
4. [Documentation](#documentation)

____


## Task 1. Test plan

 [Тест-план.pdf](Task1/testreport.pdf)

## Task 2

### Task 2.1

*Result for FirstTest*

![Alt text](allure_screenshots/FirstTest/Test9_Basket.png?raw=true "Result for FirstTest")

*Error for FirstTest*

![Alt text](allure_screenshots/FirstTest/Error_FirstTest.png?raw=true "Result for FirstTest")

____

### Task 2.2

*Result for SecondTest*

![Alt text](allure_screenshots/SecondTest/Test_11_Basket_2.png?raw=true "Result for SecondTest")

*Error for SecondTest*

![Alt text](allure_screenshots/SecondTest/Error_SecondTest.png?raw=true "Result for SecondTest")

____

### Task 2.3

*Result for ThirdTest*

![Alt text](allure_screenshots/ThirdTest/Test8_Favorites_2.png?raw=true "Result for ThirdTest")

*Error for ThirdTest*

![Alt text](allure_screenshots/ThirdTest/Error_ThirdTest.png?raw=true "Result for ThirdTest")

____

### Run Project

On the command line:

1. `mvn clean test`
2. `allure serve`
3. `allure-results`

____


### Allure Report

#### Report

![Alt text](allure_screenshots/Ower/01_allure_report.png?raw=true "Allure Report")

#### Suites

![Alt text](allure_screenshots/Ower/02_allure_suites.png?raw=true "Allure Suites")

##### Graphs
1. Status

![Alt text](allure_screenshots/Ower/01_allure_report.png?raw=true "Allure Status")

2. Severity

![Alt text](allure_screenshots/Ower/04_allure_severity.png?raw=true "Allure Severity")

3. Duration

![Alt text](allure_screenshots/Ower/05_allure_duration.png?raw=true "Allure Duration")

#### Timeline

![Alt text](allure_screenshots/Ower/06_allure_timeline.png?raw=true "Allure Timeline")

____


## Technologies

1. Programming language - [Java](https://www.java.com/)
2. Browser control - [Selenium](https://www.selenium.dev/) / [Selenide](https://ru.selenide.org/)
3. Building projects - [Maven](https://maven.apache.org/)
4. Test Automation Framework - [TestNG](https://testng.org/doc/) / [JUnit](https://junit.org/junit5/)
5. Test execution reports - [Allure2](https://docs.qameta.io/allure/)
6. Version control - [Git](https://git-scm.com/) ([GitHub](https://github.com/))

____

## Documentation

1. [Java Code Conventions](http://www.magnumblog.space/other/131-translating-java-code-conventions)
2. [Maven](https://proselyte.net/tutorials/maven/)
3. [Allure](https://docs.qameta.io/allure/)
4. [JUnit4](https://junit.org/junit4/)
