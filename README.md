# EmployeeManagementSystem_SpringBoot
A full-stack CRUD web application built using React.js, Spring Boot, and MySQL. This application allows users to manage employee data with features such as creating, viewing, updating, and deleting employee records.

## Features
📝 Add New Employees

📋 View All Employees

✏️ Edit Employee Details

🗑️ Delete Employees

📡 API Integration with Spring Boot Backend

🧑‍💻 Modular Code Structure

🎨 Responsive UI with custom footer styles

## Tech Stack
Frontend
⚛️ React.js

💅 CSS (Custom footer styling in App.css)

📦 Axios (For API requests)

Backend
☕ Java + Spring Boot

🛢️ MySQL (Database)

🧩 JPA + Hibernate

🧰 Lombok (reduces boilerplate)

🔀 Model-Mapper Utility (manual in this case via EmployeeMapper)

🛡️ Cross-Origin Resource Sharing (@CrossOrigin("*"))

## Backend Structure

/backend
  └── code.ems_backend
       ├── controller/
       │   └── EmployeeController.java
       ├── dto/
       │   └── EmployeeDto.java
       ├── entity/
       │   └── Employee.java
       ├── mapper/
       │   └── EmployeeMapper.java
       ├── repository/
       │   └── EmployeeRepository.java
       ├── service/
       │   ├── EmployeeService.java
       │   └── EmployeeServiceImpl.java
       └── exception/
           └── ResourceNotFoundException.java

  ## Runt the Project
  1. Start the Backend(SprintBoot)
     Import the backend folder into IntelliJ or Eclipse

     Configure MySQL database in application.properties

     spring.datasource.url=jdbc:mysql://localhost:3306/employees_db
     spring.datasource.username=root
     spring.datasource.password=yourpassword
     spring.jpa.hibernate.ddl-auto=update

   Backend API: http://localhost:8080/api/employees

## API Endpoints
  ![image](https://github.com/user-attachments/assets/ad08fd50-0e05-4843-b4a7-8fe9a96a25c5)

## Concepts Implemented

RESTful APIs

Dependency Injection

DTO and Entity Mapping

Error Handling (ResourceNotFoundException)

Layered Architecture (Controller, Service, Repository)

React Component-Based Design

## Author
Varshika-@varshi-git

## Output
![Screenshot 2025-04-21 130122](https://github.com/user-attachments/assets/3fd526f0-38b8-47e3-b30a-c452630ef357)


  











