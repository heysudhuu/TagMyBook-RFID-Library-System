# 📚 TagMyBook – RFID-Based Library Checkout System

**TagMyBook** is a full-stack smart library automation system using **RFID technology**, **Arduino**, and **ASP.NET Core Web API** with **SQL Server** as the backend. Built to eliminate manual errors in book check-in/check-out, it offers a modern user experience with dashboards for both students and admins.

---

## 🚀 Features

- 📖 RFID-based Book Checkout and Return
- 👨‍🎓 Student and 👩‍💼 Admin Dashboards
- 🔍 Live Book Search with Category Filters
- 📅 Return Due Date Calendar
- 📦 Option to Buy PDF/Hard Copy
- 🌗 Dark Mode Toggle
- 📲 QR Code Generation for Books
- 🧩 Secure Login & Register with Google/GitHub OAuth

---

## 🛠️ Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| Hardware     | Arduino UNO, RFID RC522             |
| Backend      | ASP.NET Core Web API                |
| Database     | Microsoft SQL Server                |
| Frontend     | HTML, CSS, Bootstrap, JavaScript    |
| Tools Used   | Postman, GitHub, Figma, VS Code     |

---

## 📐 System Architecture

![System Flow](flowchart-fun.jpg) <!-- replace with actual image link from GitHub or Imgur -->

![System Architecture](systemarc.png)


## 📸 UI Screenshots

| Welcome Page |
|--------------|---------------|-------------|
| ![welcome](WelcomePage.png) |

 | Register Page |
| ![register](registerpage.png) |

| Login Page |
| ![login](loginpage.png) |

| Student Dashboard | 
|-------------------|----------------|------------------|
| ![student](Studentpage.png) |

| Book List View | 

| ![books](StudentQRScan.png) 

| Admin Dashboard |
|![Admin](AdminPage.png)|
| Admin Manage Book |
|![Admin](AdminManageBook.png)|
| Admin RFID Manager |
|![Admin](AdminRFIDManager.png)|
| Admin Setting |
|![Admin](AdminSetting.png)|
| Admin CheckOut CheckIn Page |
|![Admin](AdminCheckOutCheckInPage.png)|
---

## 🧪 How to Run Locally

### 🔹 Backend (ASP.NET Core)

1. Open the `.sln` solution file in **Visual Studio**
2. Restore NuGet packages
3. Update the connection string in `appsettings.json`
4. Run the project — Swagger UI should open
5. Use **Postman** to test APIs (optional)

### 🔹 Frontend (HTML/CSS/JS)

1. Open the `frontend/` folder in **VS Code**
2. Right-click `index.html` and choose **“Open with Live Server”**
3. Browse the Student or Admin dashboard pages



![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/project-live-green)
![Made With](https://img.shields.io/badge/made%20with-HTML%2C%20CSS%2C%20JS-blue)


## 🧾 Project Overview

This project digitizes and automates the book issue/return process in academic libraries using RFID technology. It features two distinct dashboards — one for students to search and borrow books, and one for admins to manage the library, inventory, and user activity.
