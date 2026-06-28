# 🏫 Institute Management System

A **Java Console-Based Institute Management System** built using **Core Java**, **JDBC**, and **MySQL**, following the **MVC (Model-View-Controller)** architecture and **DAO (Data Access Object)** design pattern.

The application provides a role-based management system for **Administrators, Teachers, and Students**, enabling efficient management of student records, attendance, marks, fees, and authentication through a structured console interface.

This project focuses on clean architecture, modular design, database integration, and object-oriented programming principles.

---

# ✨ Features

* 🔐 Role-Based Login System
* 📧 Email OTP Verification for secure login
* 🤖 AI-Powered Student Assistant
* 🔌 JDBC Connectivity
* 🏛️ MVC Architecture
* 📝 Attendance Management
* 📊 Marks Management
* 💰 Fee Management
* 🔍 Student Search
* 🔒 Password Management
* ✅ Input Validation
* ⚠️ Exception Handling

---

# 🛠️ Tech Stack

| Technology                 | Purpose                      |
| -------------------------- | ---------------------------- |
| ☕ Java                     | Core Application Development |
| 🗄️ MySQL                  | Database                     |
| 🔌 JDBC                    | Database Connectivity        |
| 🏛️ MVC                    | Software Architecture        |
| 📂 DAO Pattern             | Database Layer               |
| 💻 Eclipse / IntelliJ IDEA | Development Environment      |

---

# 🏗️ Project Architecture

```text
                 User
                  │
                  ▼
              View Layer
                  │
                  ▼
          Controller Layer
                  │
                  ▼
             DAO Layer
                  │
                  ▼
             JDBC Driver
                  │
                  ▼
            MySQL Database
```

---

# 📂 Project Structure

```text
InstituteManagementSystem
│
├── controller/
├── DOA/
├── model/
├── view/
├── Util/ (Private repo)
├── Service/
└── app/
     |--- Main.java
```

---

# 👨‍💼 Admin Module

The administrator has complete control over the institute records.

### Functionalities

* ➕ Add Student
* ❌ Remove Student
* ✏️ Update Student Details
* 📋 Display All Students
* 💰 View Fee Pending Students
* 🔍 Search Student
* 👨‍🏫 Add Teacher
* 🚪 Exit

---

# 👨‍🏫 Teacher Module

Teachers can manage attendance and academic performance.

### Functionalities

* 📝 Take Attendance
* 📊 Enter Student Marks
* 🔒 Change Password
* 📖 Display Student Marks
* 🚪 Exit

---

# 🎓 Student Module

Students can securely access their academic information.

### Functionalities

* 📅 View Attendance Details
* 📈 View Marks
* 🔒 Change Password
* 🤖 Personal Bot Assistance
* 🚪 Exit

---

# 🗄️ Database Design

## Students

| Stud_ID | Stud_Name | Stud_Age | Stud_HSC_Mark | Email | Course_ID | Course_Name |  Amt_Paid | Amt_Balance | Tot_Fee | Gender | Password |
| ------- | --------- | --- | ----------- | ----------- | ----------- | ----------- |  --- | ----------- | ----------- | ----------- | ----------- |

---

## Courses

| CID | Course_Name | Fee |
| ------- | --------- | --- |

---

## Teacher Login

| Teach_ID | Teach_Name | Mail | Teach_Pass |
| ------- | --------- | --- | ----------- |

---

## Attendance

The attendance table is designed dynamically.

Example:

| Stud_ID | Stud_Name | CID | Course_Name | D10_02_2026 | D11_02_2026 | D12_02_2026 |
| ------- | --------- | --- | ----------- | ----------- | ----------- | ----------- |

📌 **Attendance columns are created automatically using the current date**, allowing attendance to be stored day-wise without predefined date columns.

---

## Marks

Example:

| Stud_ID | Stud_Name | CID | Course_Name | Java | Python | DBMS |
| ------- | --------- | --- | ----------- | ---- | ------ | ---- |

📌 **Subject columns are added dynamically** whenever marks are entered for a new course or subject.

---

# 🚀 Key Highlights

* ✅ Role-Based Authentication
* ✅ MVC Architecture
* ✅ DAO Pattern
* ✅ JDBC with PreparedStatement
* ✅ Dynamic Database Schema Updates
* ✅ Automatic Attendance Date Columns
* ✅ Dynamic Subject Columns for Marks
* ✅ Console-Based Interactive Interface
* ✅ Object-Oriented Design
* ✅ Modular Code Structure

---

# 📚 Concepts Demonstrated

* Object-Oriented Programming
* Encapsulation
* Inheritance
* Polymorphism
* Abstraction
* JDBC
* MySQL
* MVC Architecture
* DAO Pattern
* Collections Framework
* Exception Handling
* SQL Joins
* CRUD Operations
* Authentication
* Dynamic SQL Queries

---

# 👨‍💻 Author

**Imthiyaz Husain**

⭐ If you found this project useful, consider giving it a star!
