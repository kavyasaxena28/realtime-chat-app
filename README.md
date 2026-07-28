# 💬 Realtime Chat App

A modern full-stack real-time chat application built using the MERN stack with Socket.IO for instant messaging. Users can create accounts, chat in real time, update profile pictures, and enjoy a clean responsive interface.

## 🚀 Live Demo

- 🌐 Frontend: https://realtime-chat-app-nu-lake.vercel.app
- ⚙️ Backend API: https://realtime-chat-backend-pizq.onrender.com

---

## ✨ Features

- 🔐 User Authentication (JWT)
- 💬 Real-time Messaging using Socket.IO
- 👤 User Profile Management
- 🖼️ Profile Picture Upload (Cloudinary)
- 🟢 Online/Offline User Status
- 📱 Responsive UI
- 🔒 Secure Password Hashing with bcrypt
- 🍪 HTTP-Only JWT Authentication
- ☁️ Cloud Deployment (Vercel + Render)

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- DaisyUI
- Zustand
- Axios
- Socket.IO Client

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Socket.IO
- JWT Authentication
- Cookie Parser
- Cloudinary
- bcryptjs

---

## 📂 Folder Structure

```
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
├── backend
│   ├── src
│   │   ├── controllers
│   │   ├── middleware
│   │   ├── models
│   │   ├── routes
│   │   ├── lib
│   │   └── index.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/kavyasaxena28/realtime-chat-app.git
cd realtime-chat-app
```

### Install Dependencies

Backend

```bash
cd backend
npm install
```

Frontend

```bash
cd frontend
npm install
```

---

## 🔑 Environment Variables

### Backend (.env)

```env
PORT=5001

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

---

## ▶️ Run Locally

Backend

```bash
cd backend
npm run dev
```

Frontend

```bash
cd frontend
npm run dev
```

---

## 🚀 Deployment

### Frontend

- Vercel

### Backend

- Render

### Database

- MongoDB Atlas

### Media Storage

- Cloudinary

---

## 📸 Screenshots

- Login Page
 <img width="1920" height="1080" alt="Screenshot (145)" src="https://github.com/user-attachments/assets/d1a5c967-666a-4907-93dc-a62837d23805" />

- Signup Page
  <img width="1920" height="1080" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/c1613ecf-58b3-4962-92b3-006fa4810492" />

- Setting Page
  <img width="1920" height="1080" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/7921a5cd-1c0b-45b9-babf-14f1236dfbe1" />


---

## 👩‍💻 Author

**Kavya Saxena**

GitHub:
https://github.com/kavyasaxena28

LinkedIn:
www.linkedin.com/in/kavya-saxena-13361b2b8

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
