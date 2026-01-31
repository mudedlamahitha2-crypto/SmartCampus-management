🎓 Smart Campus Assistant — Hackathon Edition

A Smart, Scalable Campus Management Platform built for Hackathons

🚀 Smart Campus Assistant (SCA) is a full-stack campus management system customized and extended by me as a hackathon project, focusing on real-world scalability, clean architecture, and rapid feature delivery.

🧠 Why This Project?

Managing campus operations is messy — multiple systems, manual processes, and poor student experience.

Smart Campus Assistant solves this by providing:

One unified platform for students & admins

Role-based secure access

Automated timetables & enrollments

Real-time notifications and messaging

This version is customized for hackathon evaluation, clean demos, and future expansion.

✨ Key Features (Hackathon Focused)
🔐 Authentication & Security

Role-based login (Student / Admin)

Spring Security 6 + BCrypt hashing

CSRF-protected forms

📊 Smart Dashboards

Personalized student dashboard

Admin analytics overview

Optimized queries using JdbcTemplate

📅 Smart Timetable

Auto-generated from enrollments

No manual scheduling

Conflict-free weekly view

📚 Course & Enrollment System

Browse course offerings

Capacity-aware enrollment

Automatic waitlisting

🔔 Notifications & Events

Real-time in-app notifications

Campus announcements & events

Read/unread tracking

📝 Quiz & Messaging System

Admin-created quizzes

Student attempts & grading

Broadcast + private messaging

🛠️ Tech Stack

Backend

Java 24

Spring Boot 3.4.12

Spring Security 6

JPA / Hibernate

JdbcTemplate

Frontend

Thymeleaf

Bootstrap 5

Vanilla JavaScript

Database

MySQL 8.0 (Aiven Cloud)

Flyway migrations

SSL-secured connection

🗄️ Architecture Overview

MVC based Spring Boot architecture

Clean separation of Controller, Service, Repository

REST APIs + Server-side rendered pages

Database-driven timetable & notifications

flowchart LR
    User --> Auth
    User --> Dashboard
    Dashboard --> Enrollment
    Enrollment --> Timetable
    Admin --> Courses
    Admin --> Faculty
    Admin --> Events
    System --> Notifications

🚀 Getting Started
Prerequisites

Java JDK 24

Maven

MySQL / Aiven Cloud account

Setup
git clone https://github.com/kumarswayam13/SmartCampus-management.git
cd SmartCampus
./mvnw clean install
./mvnw spring-boot:run


🔗 App runs at: http://localhost:8080/login
🧪 Hackathon Demo Flow (Recommended)

Login as Admin

Create Courses & Faculty

Create Course Offerings

Login as Student

Enroll in courses

View auto-generated timetable

Show notifications & dashboard updates

📌 What I Customized for Hackathon

✅ Refactored README for clarity & judging
✅ Cleaned architecture & removed unused code
✅ Improved demo flow (Admin → Student lifecycle)
✅ Optimized dashboard queries
✅ Added detailed documentation & comments
✅ Prepared project for live demo & scaling

📜 Attribution

This project is based on the original repository:

🔗 https://github.com/Jdsb06/SmartCampus

I have forked, customized, documented, and extended it solely for educational and hackathon purposes, following open-source best practices.

🔮 Future Enhancements

📱 PWA support

📊 AI-based course recommendations

🔔 Push & SMS notifications

📈 Advanced analytics

👥 Student communities

⭐ Support

If you like this project:

⭐ Star the repo

🍴 Fork it

🐛 Open issues / suggestions

<div align="center">

Built with ❤️ for Hackathons & Learning

</div># SmartCampus-management
