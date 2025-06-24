# 🧠 FlowPad – MERN Stack Note-Taking Application

A full-featured, production-ready note-taking application built using the **MERN stack**: MongoDB, Express.js, React, and Node.js.FlowPad enables users to create, manage, and organize notes with a modern UI and robust backend, demonstrating practical implementation of full-stack development, API design, and deployment.


---

## 🚀 Live Demo

🌐 [View Live Application](https://flowpad.onrender.com/)  

---

## 🏗️ Tech Stack

| Layer       | Technology                                    |
|-------------|-----------------------------------------------|
| Frontend    | React (Vite), Tailwind CSS, DaisyUI, Axios    |
| Routing     | React Router DOM                              |
| Notifications | React Hot Toast                            |
| Backend     | Node.js, Express.js, Mongoose, Dotenv         |
| Database    | MongoDB Atlas                                 |
| Rate Limiting | Upstash Redis                              |
| Deployment  | Render.com, GitHub CI/CD                      |

---

## ✨ Key Features

- 🔐 Environment-secured backend with MongoDB and Dotenv
- 📝 Add, edit, delete notes with instant feedback
- 🎨 Responsive, theme-ready interface built with Tailwind CSS and DaisyUI
- 🌍 Rate limiting with Upstash Redis to protect API endpoints
- ⚡ Fast and optimized build system using Vite
- 🚀 Deployed to Render with full CI/CD via GitHub

---

## ⚙️ Local Development Setup

### 1. Clone Repository

git clone https://github.com/yourusername/FlowPad.git

### 2:Backend SetUp

 npm install
 
### 3.Environment Setup

Create .env file in /backend directory:<br>

- **🗄️ DATABASE CONFIGURATION**<br>
- MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/FlowPad
- SERVER CONFIGURATION 
PORT=5001<br>
NODE_ENV=development

- **🔒 REDIS CONFIGURATION (Upstash)**
UPSTASH_REDIS_REST_URL=https://your-redis-url.upstash.io<br>
UPSTASH_REDIS_REST_TOKEN=your-redis-token-here

### 4.Frontend Setup
- cd ../frontend
- npm install

### 5.Run
- npm run build
- npm run start

---

### **Security Features**

- 🛡️ Rate Limiting - Redis-based request throttling
- 🌐 CORS Protection - Configured for secure cross-origin requests
- 🔐 Environment Variables - Sensitive data secured
- ✅ Input Validation - Server-side data sanitization
- 🚨 Error Handling - Secure error responses


