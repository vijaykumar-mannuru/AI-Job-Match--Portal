# 🚀 AI Job Portal (MERN Stack)

An **AI-powered Job Portal Application** built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that intelligently connects job seekers with recruiters by analyzing skills, resumes, and job requirements.

---

## 🎯 Problem Statement

Traditional job portals require users to manually search and apply for jobs, often resulting in poor matches and wasted effort.

---

## 💡 Solution

This application introduces an **AI-based job matching system** that:

* Automatically analyzes resumes
* Matches candidates with relevant jobs
* Provides skill gap insights

---

## 🔥 Key Features

### 👤 User & Recruiter Authentication

* Secure login/signup using **JWT**
* Role-based access (Job Seeker / Recruiter)

### 📄 Resume Management

* Upload resumes (PDF/Image)
* Cloud storage using **Cloudinary**

### 🤖 AI Job Matching System

* Extracts skills from resumes
* Matches with job descriptions
* Generates match score
* Suggests missing skills

### 💼 Job Management

* Recruiters can post, update, delete jobs
* Users can browse & apply for jobs

### 📊 Dashboard & Analytics

* Application tracking
* Job insights for recruiters
* User activity overview

### 🔔 Notifications (Optional Enhancement)

* Job alerts
* Application status updates

### 📱 Responsive UI

* Works smoothly on mobile, tablet, and desktop

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Bootstrap / Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Atlas)

### Authentication

* JWT (JSON Web Tokens)
* Bcrypt (Password Hashing)

### File Storage

* Cloudinary

### Deployment

* Frontend: Vercel
* Backend: Render
* Database: MongoDB Atlas

---

## 🏗️ System Architecture (High-Level)

User → React UI → Express API → MongoDB
             ↓
          Cloudinary (Resume Storage)
             ↓
          AI Matching Logic

---

## ⚙️ Getting Started

### 🔧 Prerequisites

* Node.js (v18+ recommended)
* MongoDB Atlas account
* Cloudinary account

---

### 📥 Installation

```bash
git clone https://github.com/exclusiveabhi/react-job-portal.git
cd react-job-portal
```

### Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```
PORT=
DB_URL=
JWT_SECRET_KEY=
JWT_EXPIRE=
COOKIE_EXPIRE=

CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
CLOUDINARY_CLOUD_NAME=

FRONTEND_URL=
```

Run backend:

```bash
node server.js
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

### 🌐 Run Application

Open:
👉 http://localhost:5173

---

## 📈 Future Enhancements

* 🔍 Advanced AI (NLP-based resume parsing)
* 📬 Email notifications
* 💬 Real-time chat (Recruiter ↔ Candidate)
* 📊 Advanced analytics dashboard

---


## 🤝 Contributing

Contributions are welcome!

```bash
git checkout -b feature/AmazingFeature
git commit -m "Add AmazingFeature"
git push origin feature/AmazingFeature
```

---

## ⭐ Support

If you like this project:
👉 Give a **star ⭐ on GitHub**

---

## 👨‍💻 Author
🌐 Connect with me:
💼 LinkedIn: https://linkedin.com/in/vijay-mannuru-77b355405
💻 GitHub: https://github.com/vijaykumar-mannuru
