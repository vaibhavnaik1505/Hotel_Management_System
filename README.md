# 🏨 Hotel Management System

A Java-based **Hotel Management System** designed to manage hotel operations like room booking, customer handling, employee management, and billing. This project uses **Java Swing for GUI** and **MySQL for database management**.

---

## 🚀 Features

- 🔐 User Login Authentication  
- 🏢 Dashboard for managing operations  
- 🧑‍💼 Employee Management (Add / View)  
- 🛏️ Room Management (Add / Search / Update)  
- 👤 Customer Management (Check-in / Details)  
- 🔄 Check-In and Check-Out System  
- 🚗 Driver & Pickup Service Management  
- 🏬 Department Management  
- 📊 Real-time Data Display using Tables  

---

## 🛠️ Technologies Used

- Java (Swing & AWT)
- MySQL Database
- JDBC (Java Database Connectivity)

---

## 📂 Project Structure


hotel.management.system/
│
├── Login.java
├── Dashboard.java
├── Reception.java
├── HotelManagementSystem.java
│
├── AddEmployee.java
├── AddRoom.java
├── AddDrivers.java
│
├── NewCustomer.java
├── CustomerInfo.java
├── CheckOut.java
│
├── UpdateRoom.java
├── UpdateCheck.java
├── SearchRoom.java
│
├── PickUp.java
├── Employee.java
├── Department.java
├── ManagerInfo.java
│
└── conn.java


---

## ⚙️ Setup Instructions

### 1️⃣ Prerequisites

- Java JDK (8 or above)
- MySQL Server
- IDE (Eclipse / IntelliJ / NetBeans)

---

### 2️⃣ Database Setup

Create a database:

```sql
CREATE DATABASE hms;

Update database connection in conn.java:

c = DriverManager.getConnection("jdbc:mysql:///hms","root","");
3️⃣ Run the Project
Open project in your IDE
Run the main file:
HotelManagementSystem.java
Login using credentials stored in the database
🔑 Workflow
Launch Application
Login
Open Dashboard
Manage:
Rooms
Customers
Employees
Check-in / Check-out
📸 Screenshots


Login Page
Dashboard
Room Management
Customer Form
🎯 Future Enhancements
Online booking system
Payment gateway integration
Role-based login system
Cloud database integration
REST API support
🤝 Contribution

Feel free to fork this repository and contribute improvements.

📄 License

This project is for educational purposes only.
