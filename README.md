# 🔐 Secure Auth API (Spring Boot)

A backend authentication system built using Spring Boot and Spring Security with JWT-based authentication. This project demonstrates how to implement secure login, registration, and role-based access control in a REST API.

##  Features

* User Registration & Login
* JWT Token-based Authentication
* Role-based Authorization (User / Admin)
* Secure Password Encryption using BCrypt
* RESTful API design
* Spring Security integration

##  Tech Stack

* Java
* Spring Boot
* Spring Security
* JWT (JSON Web Token)
* Maven
* MySQL (or any relational DB)

##  Project Structure

The project follows a layered architecture:

* **Controller** → Handles API requests
* **Service** → Business logic
* **Repository** → Database interaction
* **Security** → JWT & authentication logic
* **Model** → Entity classes

##  API Endpoints (Sample)

* `POST /api/auth/signup` → Register new user
* `POST /api/auth/signin` → Login and get JWT token
* `GET /api/test/user` → Access for logged-in users
* `GET /api/test/admin` → Admin-only access

## ⚙️ How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/neerajmelkani/secure-auth-api-springboot.git
   ```

2. Open project in VS Code / IntelliJ

3. Configure database in `application.properties`

4. Run the application

   ```bash
   mvn spring-boot:run
   ```

##  Notes

* JWT is used for stateless authentication
* Passwords are securely hashed
* Proper role-based authorization is implemented

##  Future Improvements

* Refresh Token implementation
* Email verification system
* OAuth2 login (Google, GitHub)
* API documentation using Swagger

---

This project is built for learning and demonstrating secure backend development practices using Spring Boot.
