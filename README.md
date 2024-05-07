# Sample Spring Boot 3.0 JWT Security Project

This project uses Spring Boot 3.0 and JSON Web Tokens (JWT) to implement security. The main features and required technologies are listed below.

## Main Features
- User registration and login with JWT authentication
- Password encryption using BCrypt
- Role-based authorization via Spring Security
- Customized access denied handling
- User logout mechanism
- Refresh token

## Required Technologies
- Spring Boot 3.0
- Spring Security
- JSON Web Tokens (JWT)
- BCrypt
- Maven

## Getting Started

### Prerequisites
Ensure that you have the following installed on your local machine:
- JDK 17+
- Maven 3+

### Installation and Running
To get started with the project, do the following:
1. Clone the repository: `git clone https://github.com/followdeklerk/spring-boot-3-jwt-security.git`
2. Navigate to the project directory: `cd spring-boot-security-jwt`
3. Add database "jwt_security" to your Postgres setup
4. Build the project: `mvn clean install`
5. Run the project: `mvn spring-boot:run`

The application will now be accessible at http://localhost:8080.
