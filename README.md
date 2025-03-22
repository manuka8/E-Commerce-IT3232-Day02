# Spring Boot AppController

## Overview
This is a simple Spring Boot application that exposes RESTful API endpoints using the `@RestController` annotation. The `AppController` class provides three GET endpoints that return different string responses.

## Prerequisites
- Java Development Kit (JDK) 11 or later
- Maven or Gradle for dependency management
- Spring Boot framework

## Project Structure
```
lk.ac.vau.fas.ict.controller
│── AppController.java
```

## API Endpoints
The following endpoints are available in this application:

### 1. Get Message
- **Endpoint:** `/app/msg`
- **Method:** GET
- **Response:** `"Hello SpringBoot"`

### 2. Get Name
- **Endpoint:** `/app/name`
- **Method:** GET
- **Response:** `"My name is SpringBoot"`

### 3. Get Profile
- **Endpoint:** `/app/myProfile`
- **Method:** GET
- **Response:** `"My name is ____ and my reg no is 2020ICT__"`

## Running the Application
1. Clone or download the project.
2. Navigate to the project directory.
3. Build and run the application using:
   ```sh
   mvn spring-boot:run
   ```
   or
   ```sh
   ./mvnw spring-boot:run
   ```
4. Access the endpoints via a web browser or API testing tool (e.g., Postman) at `http://localhost:8080/app/{endpoint}`.

## Technologies Used
- Java
- Spring Boot
- Maven/Gradle

## License
This project is open-source. You may modify and distribute it as per the applicable license.

