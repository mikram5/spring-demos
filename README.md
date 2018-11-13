# Spring security demo

A demo project implementing Spring security.

This project creates a simple web application with resources that are protected by Spring Security.

The web application includes two simple views: a home page and a "Hello World" page. 

The web application is based on Spring MVC.

Spring Security is added to the application to force the user to sign in before seeing the "Hello" page.

When a user successfully logs in, they will be redirected to the previously requested page that required authentication. There is a custom "/login" page specified by loginPage(), and everyone is allowed to view it.


Prerequisites
In order to execute this program you will need have the Java JDK installed.

Built With
Gradle - Dependency Management

Acknowledgments
Created using the Spring Security Tutorial
