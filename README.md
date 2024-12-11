Student-Subject Management System
This project is a simple Spring Boot application that allows managing students and their enrolled subjects, providing RESTful APIs to interact with the system. It also includes JWT-based authentication with two roles: student and admin. The application uses an in-memory H2 database to store data.

Features
Student Management: Create and retrieve student details.
Subject Management: Create and retrieve subjects.
Many-to-Many Relationship: A student can enroll in multiple subjects.
JWT Authentication: Implementing login for student and admin roles.
In-Memory Database: Uses H2 for easy setup and testing.
REST APIs: Expose necessary endpoints for CRUD operations.
Technology Stack
Backend: Spring Boot (Java)
Database: H2 (In-Memory)
Security: Spring Security + JWT
Build Tool: Maven
Java Version: 17

Endpoints
Student Endpoints
Create Student (POST)

POST /api/students
Get All Students (GET)

GET /api/students
Authentication Endpoints
Login (POST)

POST /api/auth/login
Request Body:
json
{
  "username": "admin",
  "password": "password"
}
