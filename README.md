# 🌐 Social Media - Web App

This project is a full-stack **social media web application** that allows users to **register, log in, post photos**, and **view images uploaded by others**. The app is built using the **MERN stack** and showcases essential web development skills including user authentication, secure file uploads, and dynamic front-end rendering.

---

## 🚀 Features

- 🔐 Secure user authentication with token-based login
- 📸 Upload and view photos using efficient storage
- 👥 Browse posts from other users
- ⚙️ Structured API with Express and MongoDB
- 🧱 Interactive and responsive frontend with React

---

## 🛠️ Tech Stack Overview

### Frontend (Client)
- **React.js**: Builds a dynamic and component-based user interface.
- **Axios**: Handles API requests to interact with the backend.
- **React Router**: Enables navigation between different pages like login, register, and post feed.

### Backend (Server)
- **Node.js & Express.js**: Power the RESTful backend and handle routing, requests, and middleware.
- **MongoDB with Mongoose**: Stores user data and post metadata in a flexible document-oriented database.
- **JWT (JSON Web Tokens)**: Implements secure token-based authentication.
- **Bcrypt**: Safely hashes user passwords before storing them.
- **Multer & GridFS**: Handle file uploads and store large images directly in MongoDB.
- **Helmet & CORS**: Improve app security and manage cross-origin requests.
- **Morgan & Body-parser**: Help with HTTP request logging and parsing request bodies.

---

## 📦 Getting Started

### Prerequisites
- Node.js and npm installed
- A running MongoDB instance (local or cloud)

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/nasmed-social-media.git
cd nasmed-social-media
```

### 2. Backend Setup
```bash
cd server
npm install
```
Update the .env file in the server folder with the following:
```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```
Start the backend server:
```
nodemon index.js
```

### 3. Frontend Setup
```bash
cd ../client
npm install
npm start
```




For any query or suggestion feel free to connect...
