# Social Connect – Java Spring Boot Web Application

## 📘 Overview
Social Connect is a social networking web application developed using **Java Spring Boot**. It enables users to register, manage profiles, create posts, and view other users’ content. The project is designed to demonstrate **real-world backend development**, **MVC architecture**, and **database integration** using modern Java technologies.

---

## 🛠️ Technology Stack

### Backend
- Java (JDK 8+)
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Frontend
- HTML5
- CSS3
- Thymeleaf Template Engine

### Database
- MySQL

### Tools & Build
- Maven
- Git & GitHub
- IntelliJ IDEA / Eclipse

---

## 🧱 Project Architecture

The project follows a **layered MVC architecture**:


```text

com.kodbook
│
├── controller → Handles HTTP requests & responses
├── entities → JPA entity classes mapped to database tables
├── repositories → Data access layer (Spring Data JPA)
├── services → Business logic layer
├── Application → Main Spring Boot entry point

```


---

## ✨ Features

- User Registration & Login
- User Profile Management
- Create and Edit Posts
- View User Profiles
- Secure Data Handling
- Dynamic Web Pages using Thymeleaf
- Clean MVC-based Code Structure

---

## 📂 Resources Structure

```text

src/main/resources
│
├── static
│ └── css, js, images
│
├── templates
│ ├── index.html
│ ├── signup.html
│ ├── home.html
│ ├── createPost.html
│ ├── editProfile.html
│ ├── myProfile.html
│ └── showUserProfile.html
│
└── application.properties

```


---

## ⚙️ Configuration

### Database Configuration
Update `application.properties` with your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/social_connect
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

```

## 🚀 How to Run the Project
1. Clone the repository
```properties
git clone https://github.com/your-username/social-connect.git
```

3. Navigate to the project directory
```properties
cd social-connect
```

4. Build the project
```properties
mvn clean install
```

5. Run the application
```properties
mvn spring-boot:run
```

6. Access the application
```properties
http://localhost:8080
```

🧪 Testing Approach

Manual testing for UI and functional workflows

Verified user authentication, post creation, and profile updates

Backend debugging using logs and database validation

Tested under Agile-based development practices
