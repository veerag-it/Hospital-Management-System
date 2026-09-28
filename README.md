# 🏥 Hospital Management System

<p>
  <img src="https://img.shields.io/badge/PHP-8.x-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
</p>

A web-based **Hospital Management System** developed using PHP, MySQL, HTML, CSS, and JavaScript. The system provides a centralized platform for managing patients, doctors, appointments, OPD queues, emergency cases, beds, billing, departments, and medical history.

The project also demonstrates the practical implementation of **Data Structures and Algorithms (DSA)** concepts in a real-world hospital management scenario.

<br>

## 🚀 Overview

This project was developed as a **Data Structures and Algorithms / Web Programming academic project** to demonstrate how fundamental DSA concepts can be applied to solve real-world problems.

The system provides an easy-to-use hospital dashboard where administrators can manage hospital records while also demonstrating concepts such as **arrays, searching, sorting, queues, priority queues, stacks, linked lists, and trees**.

<br>

## ✨ Key Features

### 👤 Patient Management

* Register new patients.
* View patient records.
* Store patient information including:

  * Name
  * Age
  * Gender
  * Phone
  * Address
  * Blood Group
  * Department
* Delete patient records.
* Undo and redo patient operations.

### 👨‍⚕️ Doctor Management

* Add and manage doctors.
* Store doctor specialization and contact information.
* View available doctors.

### 📅 Appointment Management

* Schedule patient appointments.
* Assign doctors to patients.
* Track appointment status and timings.

### 🏥 OPD Queue

* Manage patients waiting for OPD consultation.
* Demonstrates the **Queue (FIFO)** data structure.

### 🚨 Emergency Management

* Manage emergency patients based on priority.
* Critical patients can receive higher priority.
* Demonstrates a **Priority Queue**.

### 🛏️ Bed Management

* Track hospital beds.
* Manage room numbers and room types.
* Monitor available and occupied beds.

### 💳 Billing

* Maintain patient billing records.
* Track bill amounts and payment status.

### 📋 Medical History

* Store patient medical history.
* Maintain diagnosis, treatment, doctor, and record date information.
* Demonstrates the concept of a **Singly Linked List**.

### 🏢 Department Management

* Manage hospital departments.
* Store department names and Heads of Department (HODs).
* Demonstrates the concept of a **Tree / Hierarchical Structure**.

### 🔎 Search & Sort

* Search patients by name or phone number.
* Sort patient records by:

  * Name
  * Age
  * ID
* Implements **Linear Search** and **Bubble Sort** using PHP arrays.

### ↩️ Undo / Redo

* Undo recent patient additions or deletions.
* Redo previously undone operations.
* Demonstrates the **Stack (LIFO)** data structure.

### 📊 Dashboard

* Displays hospital statistics such as:

  * Total Patients
  * Total Doctors
  * Total Appointments
  * Waiting Emergency Cases
* Provides quick access to frequently used hospital operations.

### 🔐 Admin Login

* Simple administrator authentication system.
* Session-based login and logout functionality.

<br>

## 🧠 DSA Concepts Implemented

One of the main objectives of this project is to demonstrate the application of DSA concepts in a practical system.

| DSA Concept            | Application in Hospital Management System |
| ---------------------- | ----------------------------------------- |
| **Array**              | Storing and processing patient records    |
| **Linear Search**      | Searching patients by name or phone       |
| **Bubble Sort**        | Sorting patient records                   |
| **Queue**              | OPD patient waiting queue                 |
| **Priority Queue**     | Emergency patient management              |
| **Stack**              | Undo / Redo operations                    |
| **Singly Linked List** | Medical history records                   |
| **Tree**               | Hospital department hierarchy             |

<br>

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* PHP

### Database

* MySQL

### Server

* WAMP / Apache

### Concepts

* Data Structures
* Algorithms
* CRUD Operations
* Session Management
* Database Management

<br>

## 📁 Project Structure

```text
Hospital_Management_System/
│
├── index.php
├── dashboard.php
├── config.php
├── header.php
├── footer.php
│
├── patients.php
├── register_patient.php
├── doctors.php
├── appointments.php
├── opd.php
├── emergency.php
├── beds.php
├── billing.php
├── departments.php
├── history.php
│
├── search_sort.php
├── undo.php
├── dsa_lab.php
│
├── logout.php
├── script.js
├── style.css
│
├── database.sql
└── README.txt
```

<br>

## 🗄️ Database

The project uses **MySQL** with the following main tables:

* `patients`
* `doctors`
* `appointments`
* `opd_queue`
* `emergency_queue`
* `medical_history`
* `beds`
* `bills`
* `departments`

The complete database structure and sample data are provided in:

```text
database.sql
```

<br>

## ⚙️ Installation & Setup

### 1. Install WAMP

Download and install **WAMP** with Apache and MySQL.

### 2. Start the Server

Open the WAMP Control Panel and start:

```text
Apache
MySQL
```

### 3. Copy the Project

Copy the project folder into:

```text
C:\WAMP\htdocs\
```

The final path should look like:

```text
C:\WAMP\htdocs\Hospital_Management_System\
```

### 4. Create the Database

Open:

```text
http://localhost/phpmyadmin
```

Import the following file:

```text
database.sql
```

The SQL file automatically creates the:

```text
hospital_management
```

database.

### 5. Configure Database

The default configuration in `config.php` is:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "hospital_management";
```

If your MySQL installation uses a password, update the `$password` value in `config.php`.

### 6. Run the Project

Open:

```text
http://localhost/Hospital_Management_System/
```

### 🔐 Demo Login

```text
Username: admin
Password: admin123
```

<br>

## ⚠️ Important

* This project requires **Apache/PHP and MySQL** to run.
* PHP files cannot be executed using VS Code Live Server alone.
* Make sure Apache and MySQL are running before opening the project.
* Keep all project files inside the same project directory.
* Import `database.sql` before using the application.

<br>

## 🎯 Project Objectives

* Develop a functional hospital management web application.
* Understand CRUD operations using PHP and MySQL.
* Apply DSA concepts to real-world problems.
* Implement searching and sorting algorithms.
* Understand practical applications of queues and priority queues.
* Implement stack-based undo and redo functionality.
* Demonstrate hierarchical data using trees.
* Build a simple and user-friendly hospital administration interface.

<br>

## 👥 Project Credits

**Veera Gupta**
Full-stack Development • Database Design • DSA Implementation • UI Development

<br>

## 📸 Project Preview


[![Hospital Management System Demo](hps.png)]([https://www.youtube.com/watch?v=YOUR_VIDEO_ID](https://youtu.be/9ND3kN_FM0U?si=mkmGa6tap9ea9ZWw))


<br>

## 📚 Academic Project

This project was developed for academic purposes to demonstrate the practical implementation of **Data Structures and Algorithms** along with **Web Development and Database Management**.

<br>

⭐ If you found this project useful, consider giving the repository a star!
