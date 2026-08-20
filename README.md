# Smart Classroom Attendance System

A full-stack web application for tracking student attendance using Face Recognition and Geolocation.

## Features
- **Student Attendance:** Face matching & Geolocation restriction.
- **Admin Panel:** Manage attendance, view analytics, export to Excel.
- **Email Notifications:** Confirming attendance to the student via email.

## Tech Stack
- Frontend: React + Vite + Tailwind CSS
- Backend: Node.js + Express + MongoDB
- AI/ML for face matching: face-api.js

## Folder Structure
- `frontend/` - React frontend (Vite)
- `backend/` - Node.js Express API

## Setup Instructions

### Prerequisites
- Node.js (v18+)
- MongoDB (Local or MongoDB Atlas)

### Backend Setup
1. Open a terminal and navigate to the `backend` folder.
   ```bash
   cd backend
   npm install
   ```
2. Create a `.env` file in the `backend` folder based on `.env.example`.
3. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend Setup
1. Open another terminal and navigate to the `frontend` folder.
   ```bash
   cd frontend
   npm install
   ```
2. Start the Vite dev server:
   ```bash
   npm run dev
   ```

## Dummy Data & Face Models
For Face Recognition to work, you will need the model files for `face-api.js` stored in `frontend/public/models`. You can download them from the `face-api.js` repository models folder and place them there.

## License
MIT
