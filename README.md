# TODO's WebApp
Easy webapp using Spring Boot which help you with your daily TODO's.

## Table of contents
* [Introduction](#intro)
* [Technologies](#technologies)
* [Setup](#setup)
* [Status](#status)
* [Sources](#sources)

### Introduction
Hello! 
I made an application where you can choose your language (available languages are: English, Polish and German) and write your name, submit it and go to your TODO's list.
Then you can add TODO and check it in checkbox when you have done your task. It's really simple app which you can open on your localhost.

### Technologies
Project is created with:
* Java 11
* Spring Boot 2.5.0
* Spring Web 2.5.0
* Spring Data JPA 2.5.0
* Flyway 7.7.3
* H2 Database 1.4.200
* HTML5
* JavaScript ES6
* Hibernate 5.5
* MySQL 8.0.26

### Setup
If u want to run this project you need to copy it to IntelliJ IDEA and run. Next step is migrate database with flyway by open terminal in IntelliJ and write `mvn flyway:migrate`
and then open you H2 Database to check that everything works. You need to run app and write in your browser in URL localhost:8080/h2-console and in JDBC URL field you need to
paste your database URL. If H2 Database works good you can go to localhost:8080 and test your app by introducing yourself, select language and add your TODO's.

### Status
Application is completed.

### Sources
This app is based on Udemy course by Mateusz Chrzonstowski : https://www.udemy.com/course/java-ambitny-start/
