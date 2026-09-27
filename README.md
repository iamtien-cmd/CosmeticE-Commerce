# Cosmetic E-Commerce – OneShop

## 1. Overview

**OneShop** is a full-featured cosmetic e-commerce application built with **Java 21**, **Spring Boot 3**, and **Thymeleaf**. The system provides essential online shopping functionalities, allowing users to browse products, view details, leave reviews, and place orders.

The application follows a layered architecture and uses **JPA** for data persistence and **Spring Security** for authentication and authorization. Its business logic is designed to reflect common e-commerce workflows, while the user interface focuses on providing a simple and convenient shopping experience.

---

## 2. Key Features

* **E-commerce business workflows**

  * Product browsing and searching
  * Product comparison and reviews
  * Shopping and order processing
  * Multiple payment options
  * Inventory management

* **Object-Oriented Design**

  * Models real-world entities and their relationships
  * Separates product information from inventory management
  * Applies OOP principles throughout the application

* **Authentication & Authorization**

  * User authentication with Spring Security
  * Role-based access control
  * Account status validation during login
  * Custom authentication success and failure handling
  * OAuth2 login with automatic role assignment
  * Remember-me authentication using cookies

---

## 3. Tech Stack

| Category        | Technologies                            |
| --------------- | --------------------------------------- |
| Backend         | Java 21, Spring Boot 3, Spring Security |
| Frontend        | Thymeleaf, HTML, CSS, JavaScript        |
| Database        | Microsoft SQL Server                    |
| ORM             | JPA                                     |
| Version Control | Git, GitHub                             |
| Build Tool      | Maven                                   |

---

## 4. Authentication

OneShop supports multiple authentication mechanisms:

* Standard username/password authentication with Spring Security
* **Remember-me** authentication using cookies
* **OAuth2** authentication
* Role-based authorization for different types of users
* Account status verification during authentication

---

## 5. Running the Application

After successfully setting up the project, the application can be accessed at:

```text
http://localhost:8080
```

---

## 6. Getting Started

### 6.1. Prerequisites

Make sure the following tools are installed:

* **JDK 21**
* **Apache Maven**
* **Microsoft SQL Server**
* **Git**

> Spring Boot's embedded server is used by default, so a separate Tomcat installation is not required.

### 6.2. Clone the Repository

```bash
git clone https://github.com/iamtien-cmd/CosmeticE-Commerce.git
```

### 6.3. Run the Application

Configure the database connection in the application's configuration file, then build and start the Spring Boot application using Maven.

Once the application starts successfully, open:

```text
http://localhost:8080
```
