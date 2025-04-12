# User Management API (Node.js + Express + MongoDB)

A simple, secure RESTful API built using **Node.js**, **Express.js**, and **MongoDB**, featuring user registration, login, JWT authentication, and basic project structure following industry best practices.

---

## 🚀 Features

- User Registration (with hashed passwords)
- User Login (JWT-based authentication)
- Protected route using middleware
- Modular structure with controllers, routes, and models
- MongoDB integration using Mongoose
- Environment variable support via dotenv

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT (jsonwebtoken)
- bcrypt.js
- dotenv

---

## 📁 Project Structure

user-api/ ├── controllers/ │ └── userController.js ├── models/ │ └── userModel.js ├── routes/ │ └── userRoutes.js ├── middleware/ │ └── auth.js ├── .env ├── server.js ├── README.md


---

## 🔐 Environment Variables

Create a `.env` file with the following:

PORT=5000 MONGO_URI=your_mongodb_connection_uri JWT_SECRET=your_jwt_secret_key


---

## 📦 Installation & Run Locally

```bash
git clone https://github.com/shibam-max/user-api-nodejs.git
cd user-api-nodejs
npm install
npm start
