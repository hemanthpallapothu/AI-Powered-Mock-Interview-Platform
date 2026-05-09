# AI-Powered Mock Interview Platform

## 📌 Project Overview

The AI-Powered Mock Interview Platform is a full-stack MERN application designed to simulate realistic technical interviews using Artificial Intelligence.

The platform allows users to upload resumes, attend AI-driven mock interviews, answer through voice or text, solve coding challenges, and receive detailed AI-generated feedback reports.

This project integrates multiple AI services including Google Gemini AI, AssemblyAI, and Murf AI to create an interactive interview experience similar to real-world technical interviews.

---

# ✨ Features

## 🔐 Authentication System
- User Registration & Login
- JWT-based Authentication
- Protected Routes
- Secure API Access

## 📄 Resume Upload & Analysis
- Upload Resume PDF
- Extract Resume Text
- AI Resume Analysis
- Personalized Interview Generation

## 🤖 AI Interview System
- AI-generated Interview Questions
- Role-based Interviews
- Technical & HR Questions
- Context-aware Follow-up Questions
- Multi-step Interview Flow

## 🎤 Voice Interview Support
- Speech-to-Text using AssemblyAI
- AI Voice Interviewer using Murf AI
- Audio Playback System
- Voice Recording Support

## 💻 Coding Interview Support
- Monaco Code Editor Integration
- Live Coding Challenges
- Code Submission & Evaluation
- Programming Language Support

## 📊 AI Feedback & Scoring
- Communication Score
- Technical Knowledge Score
- Problem Solving Score
- Confidence Evaluation
- Detailed AI Feedback Report
- Strengths & Improvement Areas

## 📚 Interview History
- View Previous Interviews
- Resume Unfinished Interviews
- Delete Interview History
- Performance Tracking Dashboard

## 🎨 UI/UX Features
- Responsive Design
- Dashboard Analytics
- Loading States
- Toast Notifications
- Smooth Navigation

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Vite
- React Router DOM
- Axios
- React Hot Toast
- Bootstrap
- CSS3
- Monaco Editor

## Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- Multer

## AI Services
- Google Gemini AI
- AssemblyAI
- Murf AI

---

# 🧠 AI Workflow

```text
1. User uploads resume PDF
        ↓
2. Backend extracts resume text using PDF parser
        ↓
3. Gemini AI analyzes resume
        ↓
4. AI generates personalized interview questions
        ↓
5. Murf AI converts questions into voice
        ↓
6. User answers through voice or text
        ↓
7. AssemblyAI converts voice → text
        ↓
8. Gemini AI evaluates answers and coding solutions
        ↓
9. Backend calculates interview scores
        ↓
10. MongoDB stores interview data and feedback
        ↓
11. AI-generated feedback report displayed to user
```

## 🤖 AI Services Workflow

### Gemini AI
- Resume analysis
- Interview question generation
- Follow-up question generation
- Code evaluation
- Feedback generation
- Performance scoring

### AssemblyAI
- Speech-to-text transcription
- Voice answer processing

### Murf AI
- AI interviewer voice generation
- Text-to-speech conversion

## 🔄 Interview Lifecycle

```text
Resume Upload
    ↓
Interview Setup
    ↓
AI Question Generation
    ↓
Voice/Text Answer Submission
    ↓
AI Evaluation
    ↓
Feedback Generation
    ↓
Interview History Storage
```

# 📂 Project Structure

```bash
project/
│
├── server/
│   ├── src/
│   │   ├── config/
│   │   │   └── gemini.config.js
│   │   │
│   │   ├── controllers/
│   │   │   ├── auth.controller.js
│   │   │   ├── interview.controller.js
│   │   │   ├── resume.controller.js
│   │   │   └── history.controller.js
│   │   │
│   │   ├── middleware/
│   │   │   ├── auth.middleware.js
│   │   │   └── upload.middleware.js
│   │   │
│   │   ├── models/
│   │   │   ├── User.model.js
│   │   │   ├── Interview.model.js
│   │   │   └── Resume.model.js
│   │   │
│   │   ├── routes/
│   │   │   ├── auth.routes.js
│   │   │   ├── interview.routes.js
│   │   │   ├── resume.routes.js
│   │   │   ├── history.routes.js
│   │   │   └── index.js
│   │   │
│   │   ├── services/
│   │   │   ├── gemini.service.js
│   │   │   ├── assemblyai.service.js
│   │   │   ├── murf.service.js
│   │   │   ├── interview.service.js
│   │   │   ├── resume.service.js
│   │   │   ├── history.service.js
│   │   │   └── auth.service.js
│   │   │
│   │   ├── utils/
│   │   │   └── prompts.utils.js
│   │   │
│   │   ├── constants/
│   │   │   └── prompts.js
│   │   │
│   │   └── app.js
│   │
│   ├── package.json
│   └── server.js
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AudioPlayer/
│   │   │   ├── VoiceRecorder/
│   │   │   ├── CodeEditor/
│   │   │   ├── InterviewCard/
│   │   │   ├── ScoreCard/
│   │   │   ├── Navbar/
│   │   │   └── ProtectedRoute/
│   │   │
│   │   ├── pages/
│   │   │   ├── LoginPage/
│   │   │   ├── HomePage/
│   │   │   ├── InterviewSetupPage/
│   │   │   ├── InterviewPage/
│   │   │   ├── FeedbackPage/
│   │   │   └── HistoryPage/
│   │   │
│   │   ├── services/
│   │   │   ├── api.js
│   │   │   ├── authService.js
│   │   │   ├── interviewServices.js
│   │   │   └── historyService.js
│   │   │
│   │   ├── context/
│   │   │   └── AuthContext.jsx
│   │   │
│   │   ├── constants/
│   │   │   └── scoreColors.js
│   │   │
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

# AI-Powered-Mock-Interview-Platform
