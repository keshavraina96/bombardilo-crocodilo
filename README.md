# QuickDesk Help Desk System

A modern full-stack Help Desk application built with:

- **Frontend**: React, TailwindCSS, Framer Motion
- **Backend**: Node.js, Express, MongoDB, JWT
- **Deployment**: Vercel (Frontend), Render (Backend)

## 📁 Folder Structure

```
bombardilo-crocodilo/
├── client/         # React Frontend
├── server/         # Node.js Backend
```

## 🚀 Quick Start

### 1. Backend (server)

```bash
cd server
npm install
npm run dev
```

Create a `.env` file in `server/`:

```
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
```

### 2. Frontend (client)

```bash
cd client
npm install
npm run dev
```

Create a `.env` file in `client/`:

```
VITE_API_URL=http://localhost:5000/api
```

---

## ✅ Features

- User Auth (JWT)
- Role-based access (User, Agent, Admin)
- Ticket creation & threaded replies
- Email notifications (optional)
- Dark mode toggle
