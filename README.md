
# 💰 Expense Tracker (MERN Stack)

A full-stack **Expense Tracker** web application built with the **MERN stack** (MongoDB, Express, React, Node). Track your daily, weekly, and monthly expenses, categorize them, and visualize your spending in charts.

---

## 🚀 Features

- 📋 Add, edit, delete expenses
- 📊 Visual expense summary with charts
- 🗂️ Categories for income & expenses
- 🔐 JWT-based authentication (Sign Up / Log In)
- 🌐 RESTful API integration (MongoDB + Express + Node)
- 🎨 Responsive React UI with modern design

---

## 🛠️ Tech Stack

| Frontend          | Backend           | Database |
|------------------|-------------------|----------|
| React.js         | Node.js, Express  | MongoDB  |
| Axios, Chart.js  | JWT Auth          | Mongoose |

---

## 📁 Project Structure
expense-tracker/
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ └── App.js
├── server/ # Node/Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
├── .env
├── package.json
└── README.md

---

## 📦 Installation

### ✅ Prerequisites:
- Node.js
- MongoDB installed locally or MongoDB Atlas cloud DB
- Express.js
- React.js

---

### 🔌 Backend Setup (server)

```bash
cd server
npm install

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
