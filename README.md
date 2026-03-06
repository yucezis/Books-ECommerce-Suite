# Books E-Commerce Suite | Full-Stack Ecosystem

This repository serves as the central documentation and architectural overview for the **BookNest** graduation project. The project is a comprehensive Full Stack E-Commerce solution developed using modern software architectures and principles. 

To prioritize sustainability, scalability, and independent deployment, the system has been modularized into three independent repositories.

### 🔗 Core System Repositories
* **[Backend API Repository](https://github.com/yucezis/books-API):** .NET 9 Web API & Entity Framework Core (Central Data Provider)
* **[Admin Panel Repository](https://github.com/yucezis/books-admin-panel-mvc):** ASP.NET Core MVC Dashboard (Administrative Operations)
* **[Mobile App Repository](https://github.com/yucezis/books-mobile-app):** Flutter Mobile Application (Customer Shopping Interface)

---

## Architectural Structure

The project is designed with an N-Layer architecture, decoupling the frontend interfaces from the core business logic. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/6d0cbe9f-9c10-4f85-892e-f0704208c531" alt="BookNest Architecture Diagram" width="600">
  <br>
  <small>This diagram illustrates the overall system architecture of the project, including the API, Admin Panel, Mobile App, and Database layers.</small>
</p>

---

## Project Highlights & Features

The management panel, backend infrastructure, and mobile application have been fully developed to simulate a real-world, production-ready environment.

### 🧠 Advanced Backend & AI Integration
-  **Google Gemini AI:** Integrated AI-powered chat to provide real-time customer support and personalized book recommendations.
-  **Robust API Architecture:** RESTful services and database integration leveraging Entity Framework Core (Code First).
-  **Security & Session:** Secure Admin login, role management, and Session handling.

### 💻 Admin Panel (Web)
-  **Category & Product Management:** Full-scope CRUD operations with stock tracking and Active/Passive status control.
-  **Customer Support Module:** Real-time messaging interface for Admins to reply to customer inquiries.
-  **Customer Management:** Data privacy masking (Hiding Name, Surname, Phone) and detailed sales history.
-  **Dashboard:** Summary data, statistical charts, and review moderation system.

### 📱 Mobile App (Cross-Platform)
-  **Shopping & Checkout:** Dynamic cart operations, multiple address management, and conditional shipping fee calculation.
-  **Authentication & Security:** User registration, login, mandatory email verification, and simulated OTP/SMS verification.
-  **Order Tracking:** Visual interface to track delivery status and automatic E-Invoice (PDF) generation.
-  **User Experience:** Dynamic "Best Sellers" sorting, advanced filtering, wishlists, and a system to rate/review books with photo uploads.

---

## Tech Stack

### Backend (API)
- .NET 9
- Entity Framework Core (Code First)
- LINQ
- SQL Server
- Swagger UI

### Admin Panel (Web)
- ASP.NET Core MVC
- Bootstrap 5 (Responsive)
- HttpClient
- HTML5 / CSS3 / JavaScript

### Mobile (Cross-Platform)
- Flutter & Dart
- Http Package
- 
---

## Installation & Setup

Since BookNest utilizes a micro-repo architecture, each layer has its own setup instructions and dependencies. To run the project on your local machine, please follow the documentation in the respective repositories:

1. **Backend API:** Please visit the **[Backend Repository]** for database configuration (`appsettings.json`), EF Core migrations (`Update-Database`), and running the local server.
2. **Admin Panel:** Check the **[Admin Repository]** to configure the API connection and run the MVC web app.
3. **Mobile App:** Visit the **[Mobile Repository]** to update the `baseUrl` with your local IPv4 address before running the Flutter application on an emulator or physical device.

---

## Developer

- **Name:** Zişan Yüce  
- **Role:** Computer Engineering Student 
- **Goal:** Developed as a comprehensive **Graduation Project**, this suite demonstrates advanced Full Stack development capabilities. It highlights a strong focus on building scalable, real-world e-commerce ecosystems, integrating a robust **.NET Core backend** with Web (MVC) and Mobile (Flutter) interfaces, and applying best practices in N-Layer Architecture and RESTful API design.

---

⭐ **If you like this project, don't forget to give the individual repositories a star!**
