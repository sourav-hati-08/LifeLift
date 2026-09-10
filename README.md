# Doctor–Patient Dashboard

### Online Doctor & Patient Management Platform

A full-stack **online healthcare management platform** that provides separate dashboards for **doctors and patients**. The system helps patients manage appointments and medical information while allowing doctors to manage patients, schedules, and consultations through a centralized dashboard.

---

## 🚀 Features

### 👨‍⚕️ Doctor Dashboard

* Doctor registration and secure login
* Manage doctor profile
* Manage availability and schedule
* View patient information
* Manage appointments
* Update appointment status
* Manage consultation records

### 🧑‍💻 Patient Dashboard

* Patient registration and login
* Create and update patient profile
* Browse available doctors
* Book appointments
* View appointment history
* Track appointment status
* View consultation information

### 🔐 Authentication

* Secure user registration and login
* JWT-based authentication
* Role-based access control
* Protected routes
* Secure password handling

---

## 🔄 Platform Workflow

```text
                    Online Healthcare Platform
                              │
                ┌─────────────┴─────────────┐
                │                           │
             Patient                      Doctor
                │                           │
          Create Profile              Create Profile
                │                           │
          Find Doctor                 Manage Schedule
                │                           │
        Book Appointment             View Appointments
                │                           │
                └─────────────┬─────────────┘
                              │
                       Consultation
                              │
                       Medical Records
```

---

## 🛠️ Tech Stack

**Frontend**

* React.js
* HTML5
* CSS3
* JavaScript

**Backend**

* Node.js
* Express.js
* REST API

**Database**

* MongoDB

**Authentication**

* JWT

**Tools**

* Git
* GitHub
* Postman
* VS Code

---

## 📁 Project Structure

```text
Doctor-Patient-Dashboard/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔒 Security

* JWT authentication
* Role-based authorization
* Protected API routes
* Password hashing
* Environment variables for sensitive configuration

> Never commit `.env` files, database credentials, API keys, or other secrets to GitHub.

---

## 🔮 Future Enhancements

* 📹 Video consultation
* 💬 Doctor–patient chat
* 🔔 Appointment notifications
* 💳 Online payment integration
* 📄 Digital prescriptions
* 📊 Health analytics dashboard
* ☁️ Cloud deployment

---

## 🎯 Objective

The objective of this project is to provide a centralized digital platform that simplifies **doctor–patient interaction, appointment management, and healthcare administration**.

---

## 📄 License

This project is developed for **educational, academic, and portfolio purposes**.

---

### ⭐ Doctor–Patient Dashboard

**Connecting Patients with Doctors through a modern digital healthcare platform.**
