## Student Management CRUD Application built using Spring Boot, MySQL, JPA, and REST APIs.  Tested using Postman.


This is a simple Student Management System built using Spring Boot, MySQL, and Postman.  
It performs basic CRUD operations(Create, Read, Update, Delete).


## Technologies Used
- Java  
- Spring Boot  
- Spring Data JPA  
- MySQL  
- Maven  
- Postman  


## Project Architecture (Simple)

Controller – Handles HTTP requests
Service – Contains business logic
Repository – Communicates with database
Entity – Represents database table

## Application flow

Postman → Controller → Service → Repository → MySQL

## API Endpoints

POST /students – Add student  
GET /students – Get all students  
PUT /students– Update student  
DELETE /students/{id} – Delete student  


## Tools Used
- Postman for testing APIs
- MySQL for database
