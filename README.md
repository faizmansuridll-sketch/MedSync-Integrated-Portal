# MedSync – Integrated Healthcare Portal

## Overview

MedSync is a full-stack web-based healthcare management system designed to simplify interactions between patients, doctors, and administrators. The platform streamlines appointment booking, doctor management, patient tracking, and healthcare communication through an integrated portal.

The project is built using Java Servlets, JSP, JDBC, Maven, and MySQL following a modular MVC-inspired architecture.

---

# Features

## Patient Module

* User Registration & Login
* Book Appointments with Doctors
* View Appointment History
* Change Password
* Responsive User Dashboard

## Doctor Module

* Doctor Login & Authentication
* View Assigned Patients
* Update Appointment Status
* Edit Profile Information
* Change Password

## Admin Module

* Admin Authentication
* Add / Update / Delete Doctors
* Manage Specialists
* View Doctors & Patients
* Monitor Appointment Activity

---

# Tech Stack

| Technology         | Usage                 |
| ------------------ | --------------------- |
| Java               | Backend Development   |
| JSP & Servlets     | Web Application Logic |
| JDBC               | Database Connectivity |
| MySQL              | Database Management   |
| Maven              | Dependency Management |
| HTML/CSS/Bootstrap | Frontend UI           |
| Apache Tomcat      | Application Server    |

---

# Project Structure

```bash
MedSync-Integrated-Portal/
│
├── src/main/java/com/hms/
│   ├── admin/
│   ├── dao/
│   ├── db/
│   ├── doctor/
│   ├── entity/
│   └── user/
│
├── src/main/webapp/
│   ├── admin/
│   ├── doctor/
│   ├── component/
│   ├── img/
│   └── WEB-INF/
│
├── pom.xml
└── README.md
```

---

# Database Setup

## Step 1: Create Database

```sql
CREATE DATABASE medsync;
```

## Step 2: Configure MySQL Credentials

Update the database credentials inside:

```bash
src/main/java/com/hms/db/DBConnection.java
```

Example:

```java
String url = "jdbc:mysql://localhost:3306/medsync";
String username = "root";
String password = "your_password";
```

---

# Installation & Run

## Clone Repository

```bash
git clone https://github.com/your-username/MedSync-Integrated-Portal.git
```

## Open in IDE

Recommended IDEs:

* IntelliJ IDEA
* Eclipse IDE
* VS Code with Java Extensions

## Configure Server

* Install Apache Tomcat
* Add project to Tomcat Server
* Configure Maven dependencies

## Run Application

Start Tomcat server and open:

```bash
http://localhost:8080/MedSync-Integrated-Portal/
```

---

# Authentication Modules

| Module  | Access                         |
| ------- | ------------------------------ |
| Admin   | Manage doctors & specialists   |
| Doctor  | Manage appointments & patients |
| Patient | Book & track appointments      |

---

# Core Functionalities

## Appointment Management

* Patients can request appointments.
* Doctors can approve/update appointment status.
* Admin can monitor overall appointment records.

## Doctor Management

* Admin can add doctors with specialization.
* Doctors can update profile information.
* Doctors can manage patient interactions.

## Security Features

* Session-based authentication
* Login validation
* Password update functionality
* Role-based access control

---

# Screens Included

* Home Page
* Admin Dashboard
* Doctor Dashboard
* Patient Dashboard
* Appointment Booking Page
* Login & Registration Pages

---

# Future Improvements

* Online Video Consultation
* Payment Gateway Integration
* Email/SMS Notifications
* AI-based Appointment Recommendations
* Medical Report Upload System
* JWT Authentication & REST APIs
* Cloud Deployment

---

# Learning Outcomes

This project demonstrates:

* Java Web Development
* MVC Architecture Concepts
* JDBC & Database Operations
* Session Handling
* CRUD Operations
* Authentication & Authorization
* Full-Stack Application Development

---

# Author

**Faiz Mansuri**

Java Backend Developer | Full Stack Developer

---

# License

This project is developed for educational and portfolio purposes.
