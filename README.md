# Project Title: Automation of Web Form using JUnit  

### Project Summary: A web form having fields such as Name (Mandatory), Number, Today's date, Email, Tell us a bit about yourself, Upload a document and a checkbox (Mandatory) has been automated using JUnit, a framework of Selenium. Later, the submission has been asserted by matching the message "Thank you for your submission!" in the result page.  

## Prerequisites  
* JDK 11
* IntelliJ IDEA
* Gradle
* Library: Selenium

## How to setup the environment?  
* Copy library name from the Gradle section on [https://mvnrepository.com/artifact/com.googlecode.json-simple/json-simple/1.1.1](https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java/4.22.0) and paste it in build.gradle file in the project folder
* Click on the gradle icon on IntelliJ IDEA
* Click on the 'Reload All Gradle Projects' icon

## How to run?  
Run the following command in the terminal inside the project directory:  
`gradle clean test`  

## Output:  
![junit_formsubmission_report](https://github.com/user-attachments/assets/02f0fefc-834a-4d89-b3b9-73e6b7c1d388)
