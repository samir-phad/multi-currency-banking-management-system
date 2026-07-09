# Multi-Currency Banking Management System

## Overview

A secure Banking Management System developed using Java, Spring Boot, Spring Security, JWT, Hibernate/JPA, and PostgreSQL. The application provides secure authentication and supports multi-currency account management, fund transfers, currency conversion, card services, and transaction history through RESTful APIs.

---

## Features

- User Registration & Login
- JWT Authentication & Authorization
- Multi-Currency Bank Accounts
- Fund Transfer Between Accounts
- Currency Conversion
- Debit/Credit Card Management
- Transaction History
- Exchange Rate API Integration
- Secure REST APIs

---

## Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring Security
- JWT
- Hibernate / JPA

### Database
- PostgreSQL

### Build Tool
- Maven

### API Testing
- Postman

### Version Control
- Git & GitHub

---

## Project Structure

```
src
 ├── config
 ├── controller
 ├── dto
 ├── entity
 ├── filters
 ├── repository
 ├── service
 ├── util
 └── resources
```

---

## REST API Modules

### Authentication

- Register User
- Login

### Accounts

- Create Account
- Get Accounts
- Find Account

### Banking

- Transfer Money
- Currency Conversion
- Exchange Rates

### Card

- Create Card
- Credit Card
- Debit Card

### Transactions

- View Transaction History

---

## Database

- PostgreSQL
- Hibernate/JPA ORM
- Automatic Table Creation

---

## Security

- JWT Authentication
- Password Encryption
- Protected REST APIs
- Stateless Authentication

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/samir-phad/multi-currency-banking-management-system.git
```

### Open Project

```
IntelliJ IDEA
```

### Configure PostgreSQL

Update the following properties inside

```
src/main/resources/application.properties
```

```properties
spring.datasource.url=
spring.datasource.username=
spring.datasource.password=
```

### Run Project

```bash
./mvnw spring-boot:run
```

Server starts at

```
http://localhost:8080/api/v1
```

---

## API Testing

Use Postman to test all REST APIs.

---

## Future Improvements

- React Frontend
- Admin Dashboard
- Email Notifications
- Loan Management
- Fixed Deposit Module
- Mobile Banking UI

---

## Author

**Samir Phad**

GitHub:
https://github.com/samir-phad
