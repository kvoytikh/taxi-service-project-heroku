## Taxi Service Web Application

#### Heroku version: https://taxi-service-prj.herokuapp.com

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
I have created this "Taxi service" project to demonstrate my expertise in Java Core, OOP, SOLID concepts, JDBC, RDBMS, 
JDBC and WEB-technology.

## Features provided by the application for registered users

1. User(driver) can create new car or manufacturer
2. Add driver to a specific car
3. View all drivers, cars and manufacturers
4. View all cars by logged-in user
5. Delete car, driver or manufacturer

## Technologies
In project these technologies have been used:

* Java 11
* MySQL
* Tomcat 9.0.54 
* Javax servlet API
* JSTL


## Setup
There are few steps to deploy this project:

1. Install MySQL 
2. Install Tomcat 9.0.54 version. Link -> https://tomcat.apache.org/download-90.cgi
3. Fork this project to your repository 
4. Clone it using one of the "Code" options, which is more suitable for you 
5. In resources directory you can find init_db.sql file. Use it to initialize you database 
6. Add some data to DB 
7. Go to the ConnectionUtil class located in src/main/java/mate/util and add your url to DB, login, password and JDBC driver there. (Be careful with adding URL. You should add a Timezone to it too)
8. Configure your Tomcat. (P.S. Your application context needs to be as "/")
9. Run this project using Tomcat's local server


**Run online version - deployment on Heroku** https://taxi-service-prj.herokuapp.com
