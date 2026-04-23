# 💼 Online Invoicing System (PHP)

A full-featured **Online Invoicing System** built using PHP, MySQL, Bootstrap, and JavaScript.
This system helps businesses manage invoices, customers, payments, and financial reports efficiently.

---

## 📌 Overview

The system provides two roles:

* 👤 **User Panel** – Manage invoices, clients, and transactions
* 🛠 **Admin Panel** – Full control over system data and users

Users can generate invoices, track payments, and analyze revenue, while admins can manage the entire system.

---

## 🛠 Tech Stack

* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Server:** XAMPP / Apache

---

## ✨ Features

### 🔐 Authentication & Security

* User Registration & Login
* Password Hashing (BCrypt)
* Role-Based Access Control (Admin/User)

### 📄 Invoice Management

* Create, Edit, Delete Invoices
* Auto Invoice Numbering
* Invoice Status Tracking (Paid, Unpaid, Overdue)
* GST-Compliant Invoices

### 👥 Client & Product Management

* Client Management
* Product/Service Catalog
* Tax & Discount Management

### 💰 Financial Features

* Expense Tracking
* Revenue Reports
* Payment History
* Account Statements

### 📊 Advanced Features

* Invoice PDF Generation
* Email Notifications
* Recurring Invoices
* Multi-Currency Support
* Data Import/Export

---

## 📸 Screenshots

![Dashboard](https://github.com/user-attachments/assets/fa070219-eec5-4b02-8928-b15e8dc235d8)

---

## 🖥️ Supported Operating Systems

* Windows
* macOS
* Linux

---

## ⚙️ Installation Guide

### Step 1: Setup Environment

* Install XAMPP
* Start **Apache** and **MySQL**

### Step 2: Project Setup

```bash
Copy project folder → xampp/htdocs/
```

### Step 3: Database Setup

1. Open: http://localhost/phpmyadmin/
2. Create database: `invoicing`
3. Import file: `DATABASE/invoicing.sql`

### Step 4: Run Project

```bash
http://localhost/Invoice-System-In-PHP
```

---

## 🔐 Security Improvements (Important)

* Passwords stored using hashing (BCrypt)
* Input validation & sanitization
* Prepared statements (SQL Injection protection)

---

## 📁 Project Structure

```bash
Invoice-System-In-PHP/
│── admin/
│── user/
│── database/
│── assets/
│── config/
│── index.php
│── login.php
│── register.php
```

---

## 🚀 Future Enhancements

* REST API integration
* Payment Gateway (Razorpay/Stripe)
* Advanced Analytics Dashboard
* Mobile App Integration

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit pull requests.

---

## 📜 License

This project is for educational purposes only.

---

## 👨‍💻 Author

**Rahul Kumar**
B.Tech CSE (IoT) | Java Developer | Backend Enthusiast

---
