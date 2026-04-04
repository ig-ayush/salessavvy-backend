# SalesSavvy Backend

SalesSavvy Backend is a scalable e-commerce backend built using Spring Boot.  
It provides secure authentication, product management, and order processing through RESTful APIs.  
Designed with modular architecture to handle real-world application workflows efficiently.

## Features
- JWT-based authentication and authorization
- Role-based access control (Admin & Customer)
- Product, cart, and order management APIs
- Secure password handling and validation
- Payment integration support

## Tech Stack
- Java
- Spring Boot
- Spring Security (JWT)
- MySQL
- REST APIs
- Docker

## Project Structure
- Controllers – API endpoints
- Services – Business logic
- Repositories – Database layer
- Entities – Data models
- Security – Authentication & JWT setup

## Getting Started

### Prerequisites
- Java 17+
- Maven
- MySQL
- Docker (optional)

### Setup
```bash
git clone https://github.com/ig-ayush/salessavvy-backend.git
cd salessavvy-backend
mvn clean install
mvn spring-boot:run
