# NSBM StudentHubb

### A Student Management System

**StudentHubb** is a web-based student management system developed using **Java and Spring Boot**. The system is designed to manage student information efficiently and provide essential student management functionalities through RESTful APIs.

The project focuses on simplifying student record management, secure authentication, and efficient data handling.

---

## Features

- **Student Management (CRUD)**
  - Add new students.
  - View student details.
  - Update existing student information.
  - Delete student records.

- **Student Information Management**
  - Student ID (Auto-generated Primary Key)
  - Student Name
  - Email Address (Unique)
  - Batch
  - GPA

- **Pagination**
  - Retrieve student records across multiple pages.
  - Improve data management when handling large numbers of students.

- **Sorting**
  - Organize student records based on selected fields.

- **User Authentication**
  - Login functionality.
  - Database-based user role management.
  - Encrypted password storage.

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Java | Backend programming |
| Spring Boot | Backend framework |
| Spring Data JPA | Database operations |
| REST API | Client-server communication |
| SQL Database | Data storage |
| Maven | Dependency management |
| IntelliJ IDEA | Development environment |
| Postman | API testing |
| Git & GitHub | Version control |

---

## Project Structure

```text
StudentHubb/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── .../
│   │   │       ├── controller/
│   │   │       ├── service/
│   │   │       ├── repository/
│   │   │       ├── model/
│   │   │       └── ...
│   │   │
│   │   └── resources/
│   │       └── application.properties
│   │
│   └── test/
│
├── pom.xml
└── README.md
```

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project

Open the cloned project using IntelliJ IDEA or your preferred Java IDE.

### 3. Configure the Database

Update the database configuration in:

`src/main/resources/application.properties`

Configure your database URL, username, and password.

### 4. Install Dependencies

Use Maven to install the required dependencies.

```bash
mvn clean install
```

### 5. Run the Application

Run the main Spring Boot application class from your IDE.

Or use:

```bash
mvn spring-boot:run
```

The application will start on the configured server port.

---

## 🧪 API Testing

The REST APIs can be tested using **Postman**.

Test the available endpoints for:

- Creating student records.
- Retrieving student information.
- Updating student details.
- Deleting student records.
- Pagination and sorting.

---

## 🎯 Project Objectives

- Develop a student management system using Spring Boot.
- Implement RESTful API development.
- Understand CRUD operations and database integration.
- Implement pagination and sorting.
- Apply authentication and role-based access management.
- Improve practical backend development skills.

---

## Developer

**W.A.D. Raveesha Kavindi**

Computer Science Undergraduate  
NSBM Green University

---

## Project Status

**Development Project**

Developed as part of university coursework to gain practical experience in Java, Spring Boot, backend development, database management, and REST API development.


