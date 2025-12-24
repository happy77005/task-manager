# Task Manager

Task Manager is a simple full-stack application built using a Spring Boot backend and a basic frontend. The project demonstrates a clean backend architecture following standard Spring Boot layering principles.

---

## Project Description

This application provides basic task management functionality through RESTful APIs. It is designed to showcase how controllers, services, repositories, and entities work together in a Spring Boot application.

---

## Backend Package Structure

- controller  
  Handles incoming HTTP requests and exposes REST APIs for task operations.

- entity  
  Contains domain models representing application data.

- repository  
  Manages database interactions using Spring Data repositories.

- service  
  Implements business logic and coordinates between controllers and repositories.

- TaskManagerApplication  
  The main entry point that bootstraps the Spring Boot application.

---

## Technology Stack

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- Maven
- HTML, CSS, JavaScript (basic frontend)

---

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven
- Git

---

### Running the Backend
Clone the repository
git clone https://github.com/happy77005/task-manager.git
cd task-manager/backend
- Start the application
mvn spring-boot:run
- Application runs on
http://localhost:8080
---
### Running the Frontend
- Navigate to the frontend directory
cd task-manager/frontend
- Open `index.html` in a browser or serve it using a local server
---
## API Endpoints
- GET /tasks  
  Retrieve all tasks

- POST /tasks  
  Create a new task

- PUT /tasks/{id}  
  Update an existing task

- DELETE /tasks/{id}  
  Remove a task
---
## Future Improvements

- Persistent database integration
- User authentication and authorization
- Improved frontend UI
- Validation and global exception handling
- Docker and cloud deployment support
---
## License
This project is licensed under the MIT License.
---
## Author
Hari Preetham
