# REST API with Spring Boot

A simple standard REST API built using **Spring Boot**.  
This project demonstrates basic CRUD (Create, Read, Update, Delete) operations with a clean and modular structure.

---

## Features
- RESTful endpoints
- CRUD operations
- JSON request/response
- In-memory database (H2) for development
- Standard project structure

---

## Tech Stack
- **Java 17** (or your version)
- **Spring Boot** (3.x+)
- **Spring Web**
- **Spring Data JPA**
- **H2 Database** (for testing/development)
- **Maven/Gradle** (build tool)

---

## Project Structure
src/main/java/com/example/restapi
├── controller # REST controllers (expose APIs)
├── service # Business logic layer
├── repository # Database access layer
├── model # Entity/DTO classes
└── RestApiApplication.java 


---

## Getting Started

### Prerequisites
- Install **Java 17+**
- Install **Maven/Gradle**
- IDE (IntelliJ / Eclipse / VS Code)

### Run the application
```bash
# Clone the repo
git clone https://github.com/iamrautela/rest-api-springboot.git
cd rest-api-springboot

# Run with Maven
mvn spring-boot:run

# OR build and run
mvn clean package
java -jar target/rest-api-0.0.1-SNAPSHOT.jar

