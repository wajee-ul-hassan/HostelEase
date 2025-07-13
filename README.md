# 🏨 HostelEase – Hostel Management System

**HostelEase** is a powerful and easy-to-use hostel management system built with the **MERN Stack** (MongoDB, Express.js, React, Node.js) and **Redux** for state management.

It helps administrators manage student details, monitor attendance, and control user access with ease — all from a central dashboard.

---

## 🚀 Features

* 🔐 **Authentication**

  * Secure registration and login
  * Role-based access control (Admins only for sensitive actions)

* 👨‍🎓 **Student Management**

  * Add, edit, and delete student records
  * Track student whereabouts

* 📅 **Attendance System**

  * Take daily attendance
  * View complete attendance history
  * Download attendance as `.csv`
  * Delete attendance of previous *n* days

* 👥 **User Management**

  * View and manage user list
  * Edit user admin privileges
  * Admin-only data control and access

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/hostelease.git
cd hostelease
```

### 2. Install Dependencies

```bash
# Install backend dependencies
npm install

# Move to frontend and install dependencies
cd frontend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add the following:

```env
NODE_ENV=development     # or production
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

---

## 🧪 Scripts

### Backend

```bash
npm run dev       # Start backend in development mode
npm start         # Start backend in production
```

### Frontend

```bash
cd frontend
npm start         # Start React app
```

---

## 📁 Folder Structure

```
hostelease/
│
├── backend/         # Express server, routes, models, controllers
├── frontend/        # React app with Redux
└── .env             # Environment variables
```

---

