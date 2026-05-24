# Banking Portal API

A secure backend Banking Portal system built using Java and Spring Boot. The project provides RESTful APIs for managing users, accounts, and financial transactions with secure authentication and role-based authorization.

---

## 🚀 Project Overview

This project simulates core banking operations such as user registration, login, account management, and fund transfers. It is designed using a layered architecture to ensure clean separation of concerns, scalability, and maintainability.

The project demonstrates backend development skills using Spring Boot, REST APIs, JWT authentication, and MySQL integration.

---

## 🛠️ Tech Stack

- Java  
- Spring Boot  
- Spring Security  
- JWT Authentication  
- Spring Data JPA  
- MySQL  
- Maven  

---

## ✨ Features

- User registration and login system  
- Secure authentication using JWT  
- Role-based access control (Admin / User)  
- Account creation and management  
- Fund transfer between accounts  
- Transaction history tracking  
- Secure REST API endpoints  

---

## 🧱 Architecture

The application follows a layered architecture:

- Controller Layer → Handles HTTP requests  
- Service Layer → Business logic implementation  
- Repository Layer → Database interactions  
- DTO Layer → Request and response models  

---

## 🔐 Security Implementation

- Spring Security integration for API protection  
- JWT token-based authentication  
- Password encryption before storing in database  
- Role-based endpoint access control  

---

## 🗄️ Database Configuration

This project uses **MySQL** as the database.

### 📌 Create Database
This project uses **MySQL** as the database.
Create Database 
CREATE DATABASE banking_db;

### 📌 application.properties Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/banking_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
