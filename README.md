# Real-Time Chat App 💬

A real-time messaging platform supporting 1:1 chats, media sharing, and socket-based communication.

🔗 [Live Demo](https://chat-app-8mca.onrender.com)

---

## ⚙️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **State Management**: Zustand
- **Realtime Communication**: Socket.io
- **Media Handling**: Cloudinary
- **Authentication**: JWT

---

## ✨ Features

- 🔐 JWT-based user authentication
- 💬 One-to-one private messaging
- 🖼️ Image upload via Cloudinary
- 🟢 Realtime user presence & typing indicators
- ⚡ Zustand for global state management
- 📱 Responsive & accessible UI

---

## 📁 Folder Structure

```bash
chat-app/
│
├── frontend/         # React client
│   └── ...
│
├── backend/          # Express API + Socket.io
│   └── ...
│
└── README.md
```

---

## Setup .env file

```bash
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```
---

## Setup Instructions

Clone the repo

```bash
git clone https://github.com/harshhudda/chat-app.git
cd chat-app
```

Install dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```
Start the server

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```
