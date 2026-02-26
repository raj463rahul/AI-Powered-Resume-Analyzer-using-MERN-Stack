💬 AI Resume Scorer Application (MERN Stack)
A full-stack AI-powered Resume Scoring web application built using the MERN stack. Users can register/login, upload their resumes (PDF), and receive an AI-based score based on resume quality, skills, and content analysis. The system stores resume history and provides structured feedback.

🚀 Features
🔐 User Authentication (Firebase-based)
📄 Resume Upload (PDF only)
🧠 AI-Based Resume Scoring System
📊 Resume Score Dashboard
📜 Resume History (stored in MongoDB)
📂 Secure File Handling with Multer
🎨 Clean & Responsive UI (React + Vite)
👨‍💼 Admin Monitoring Support

🛠 Tech Stack

Frontend

React
Vite
Axios
Firebase Authentication
CSS / Modern UI Styling

Backend

Node.js
Express.js
MongoDB with Mongoose
Multer (File Upload Handling)
CORS
Dotenv

📁 Project Structure

public_ai_resume_mern-main/
│
├── backend_ai/            # Backend (Node + Express)
│   ├── Controllers/
│   ├── Models/
│   ├── Routes/
│   ├── utils/
│   ├── uploads/
│   └── index.js
│
└── mern_ai/               # Frontend (React + Vite)
    ├── src/
    │   ├── component/
    │   ├── utils/
    │   └── App.jsx
