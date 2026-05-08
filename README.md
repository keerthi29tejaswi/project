# Task Manager API
A Spring Boot REST API for managing users and tasks.

## Features
- User CRUD
- Task CRUD
- Pagination
- Sorting
- Filtering
- Analytics endpoint
- Global exception handling
- Swagger API docs
  
## Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven

## Setup
1. Clone Repository
bash
git clone https://github.com/yourusername/task-manager.git
cd task-manager
2. Create PostgreSQL Database
sql
CREATE DATABASE taskdb;
3. Configure application.properties
properties
spring.datasource.username=postgres
spring.datasource.password=postgres
4. Run Application
bash
mvn spring-boot:run

## Swagger Docs
http://localhost:8080/swagger-ui.html

## API Endpoints
### Users
- POST /users
- GET /users

### Tasks
- POST /tasks/{userId}
- GET /tasks

### Analytics
- GET /analytics
