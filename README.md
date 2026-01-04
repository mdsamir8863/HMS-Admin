# 🏥 Hospital Management System (HMS) – Admin Panel

This is the **admin panel** for the Hospital Management System (HMS).  

Admins can manage doctors, view and approve appointments, monitor revenue, and access all system data securely.

---

## ✨ Features

### 👤 Admin Authentication
- Secure login for admins only
- JWT-based authentication
- Protected routes

---

### 🧑‍⚕️ Doctor Management
- Add new doctors
- Remove or edit existing doctors
- Manage doctor profiles and specialization

---

### 📅 Appointment Management
- View all appointments
- Approve or reject patient appointment requests
- Track status of appointments

---

### 💳 Billing & Revenue
- View all payments
- Track revenue per doctor and overall
- Export billing reports (optional)

---

### 📱 Responsive UI
- Mobile-friendly dashboard
- Clean, professional interface
- Quick access to important data

---

## 🛠 Tech Stack

- React.js (Vite)
- Tailwind CSS
- Redux (for state management)
- Axios (for API calls)
- React Router
- Node.js + Express backend integration
- MongoDB database

---

## 📂 Project Structure

admin/
├── src/
│ ├── components/
│ ├── pages/
│ ├── services/
│ ├── store/
│ ├── routes/
│ └── main.jsx
├── public/
├── package.json
├── vite.config.js
├── .gitignore
└── README.md