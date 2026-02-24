# GYM_DBMS


# 🏋️ Gym DBMS – MySQL Database Project

## 📌 Overview
This repository contains the MySQL database schema for a **Gym Management System**.  
The database is designed to manage gym members, instructors, memberships, workout plans, and payments.

This project can serve as a backend database for gym management software or as an academic DBMS project.

---

## 🗄️ Database Name
`gym_dbms`

---

## 📊 Tables Included

The database consists of the following tables:

- **members** – Stores gym member information  
- **instructors** – Stores instructor / trainer details  
- **memberships** – Tracks membership plans and subscriptions  
- **memberworkouts** – Stores workout assignments or logs  
- **workoutplans** – Defines available workout programs  
- **payments** – Stores payment and billing records  
- **members_seq** – Sequence/helper table (if applicable)

---

## 🧱 Database Description

The schema models a typical gym management workflow:

✔ Member registration and management  
✔ Instructor / trainer management  
✔ Membership tracking  
✔ Workout planning and assignments  
✔ Payment and billing management  

The design follows relational database principles with structured tables and relationships.

---

## ⚙️ Requirements

To run this database locally, you need:

- MySQL Server (8.0 or later recommended)
- MySQL Workbench (optional)

---

## 🚀 How to Import the Database

### Using MySQL Workbench

1. Open **MySQL Workbench**
2. Navigate to:

   `Server → Data Import`

3. Select:

   `Import from Self-Contained File`

4. Choose the SQL file:

   `gym_dbms.sql`

5. Click **Start Import**

---

## 🛠️ Manual Database Setup (Optional)

If required, create the database manually:

------------------------------------------------------------------------------------------------------------------------------------------------------------------



```sql
CREATE DATABASE gym_dbms;
USE gym_dbms;
