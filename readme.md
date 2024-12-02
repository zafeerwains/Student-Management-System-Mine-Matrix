# Student Management System

## Overview
The **Student Management System** is a robust application designed to manage students, teachers, and classes efficiently. It provides distinct dashboards for students, teachers, and the superadmin to handle various tasks like attendance tracking, roll call management, and detailed record-keeping.

---

## Features and Roles

### 1. Authentication & User Management
- **Login/Signup**:
  - Supports multiple roles: Student, Teacher, and Superadmin.
- **Forgot/Reset Password**:
  - Allows users to reset their password securely.
- **Email Verification**:
  - Ensures email authenticity before granting access.
- **Protected Routed**:
  - Ensure No one can access the other routes


---

### 2. Role-Specific Dashboards

#### A. Student Dashboard
- **Attendance Tracking**:
  - View attendance records for each class, categorized by teacher.
- **Personal Information**:
  - Update profile details (e.g., name, email, contact).

#### B. Teacher Dashboard
- **Roll Call Management**:
  - Mark attendance for assigned classes.
  - View and edit attendance records.
- **Student Performance**:
  - View and comment on student participation or grades.

#### C. Superadmin Dashboard
- **Student Management**:
  - Add, delete, or update student records.
  - View detailed student information and their attendance.
- **Teacher Management**:
  - Add, delete, or update teacher records.
  - Assign teachers to specific classes.
  - can change the role of student to teacher .
  
---
# Project APIs Development

 Below is the list of tasks assigned to team members, along with a brief description of their responsibilities.

---

## Task Assignment

1. **Rizwan**
   - **Task:** Design the schema and attach the database to the server.
   - **Details:** Define and structure the database tables, relationships, and indexes. Ensure the database is properly connected to the server.

2. **Usman Saeed**
   - **Task:** Create the API for Teacher Management from the superadmin section.
   - **Details:** Develop APIs to handle CRUD operations for managing teachers, including adding, updating, deleting, and viewing teacher records.

3. **Faisal**
   - **Task:** Create the API for Student Management from the superadmin section.
   - **Details:** Develop APIs to handle CRUD operations for managing students, including adding, updating, deleting, and viewing student records.

4. **Zeeshan Shafi**
   - **Task:** Create the API for the Teacher Dashboard.
   - **Details:** Develop APIs to manage and display teacher-specific data and functionalities, such as schedules, performance metrics, and notifications.

5. **Zeeshan Ghani**
   - **Task:** Create the API for the Student Dashboard.
   - **Details:** Develop APIs to manage and display student-specific data and functionalities, such as progress reports, schedules, and announcements.

6. **Sajjad Ali**
   - **Task:** Develop the Login and Signup API.
   - **Details:** Implement secure login and signup APIs, including validation, token generation, and user authentication.

7. **Muzammal Hussain**
   - **Task:** Develop Forgot/Reset Password, Verify Email, and Logout APIs.
   - **Details:** 
     - Create APIs to handle password recovery and reset processes.
     - Develop an email verification API to confirm user registrations.
     - Implement a logout API to end user sessions securely.

---





