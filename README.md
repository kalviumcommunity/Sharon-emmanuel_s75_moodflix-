🧠 MoodFlix – Capstone Project Plan


🎓 Capstone Project Idea Brief
## Project Title:
MoodFlix – AI-Powered Mood-Based Movie Recommendation System

## Problem Statement:
With the overwhelming volume of content available on streaming platforms, users often struggle to find something that truly matches how they feel or want to feel. Traditional recommendation engines are based on watch history or popularity, but they lack emotional context.

## Project Objective:
To build a full-stack web application that recommends movies based on the user’s current and desired mood, using AI, emotion-mapping, and public movie APIs. The goal is to personalize content discovery and enhance the user's viewing experience.

## Key Features:
Mood selection via UI or emotion detection (AI/Camera)


Personalized movie recommendations using TMDb API


User authentication (JWT-based login/signup)


Watchlist & movie rating system


Admin dashboard for managing content


Dark/light mode toggle, responsive UI


Deployment with domain and live demo



## Technology Stack:
Layer
Tech Used
Frontend
React, Vite, TailwindCSS, Framer Motion
Backend
Node.js, Express.js, JWT, bcrypt
Database
MongoDB (with Mongoose)
AI/ML
TensorFlow.js or face-api.js (for mood detection)
APIs
TMDb API, JustWatch API
Dev Tools
Postman/Bruno, GitHub, Netlify/Render
Design
Figma


## Target Users:
Individuals looking for emotionally relevant movies or series


People who struggle to choose content on OTT platforms


## 📅 Week 1: Planning, Setup, and Core Features


april 20 to 27
🗓️ Day 1–2: Project Planning & Setup
Goals:
Finalize features and tech stack


Design wireframes using Figma


Setup GitHub repo with separate frontend and backend folders


Initialize backend (Express + MongoDB)


Initialize frontend (Vite + TailwindCSS)


Deliverables:
Figma wireframes


Folder structure


Environment setup



🗓️ Day 3–5: Authentication System
Goals:
Implement user registration and login (JWT-based)


Build login, signup pages with form validation


Store JWT in localStorage


Setup protected routes in frontend


Deliverables:
/api/auth/register and /api/auth/login routes


Login/Signup UI


Auth context in React



🗓️ Day 6–7: Mood Selection Interface
Goals:
Create mood selection page (emoji or dropdown)


Capture current mood & target mood


Plan mood → genre mapping


Deliverables:
MoodSelection.jsx component


Mood state management


Mood-to-genre logic



## 📅 Week 2: Movie Recommendation System + UI Components

april 28 to may 5

🗓️ Day 8–9: Recommendation Logic
Goals:
Integrate TMDb API


Create backend /api/recommend route


Query movies using mood→genre mapping


Deliverables:
Dynamic movie fetching


/api/recommend working with selected moods



🗓️ Day 10–11: Display Movie Recommendations
Goals:
Design and render movie cards (poster, title, rating)


Implement filtering (e.g., rating, release year)


Show loading and error states


Deliverables:
Recommendations.jsx page


Movie card components


Responsive grid layout



🗓️ Day 12–13: Watchlist & Ratings
Goals:
Add "Add to Watchlist" and "Rate" functionality


Create watchlist backend routes


Display user watchlist in UI


Deliverables:
/api/watchlist CRUD routes


Watchlist page UI


Star rating system



🗓️ Day 14: Testing & Debugging Core Features
Goals:
Test auth, mood selection, recommendations, and watchlist


Debug API and UI issues


Use Postman/Bruno for backend tests


Deliverables:
Functional end-to-end flow


Bug fixes


Refined UI



## 📅 Week 3: AI + Admin + Polish + Deployment
May 6 to 16

🗓️ Day 15–16: AI Mood Detection (Optional)
Goals:
Integrate webcam mood detection using TensorFlow.js or face-api.js


Automatically detect user’s mood (optional feature)


Deliverables:
Webcam component


Mood prediction → movie suggestions



🗓️ Day 17–18: Admin Dashboard
Goals:
Create pages for admin to manage movies, users, and feedback


Implement role-based access control


Deliverables:
/admin route with protected access


Admin UI pages for managing data



🗓️ Day 19–20: Final UI Polish + Feedback Page
Goals:
Improve responsiveness, animations (Framer Motion)


Add feedback/contact page


Enable light/dark theme toggle


Deliverables:
Fully responsive app


UI animations


Extra pages (404, feedback, etc.)



🗓️ Day 21: Final Testing & Deployment
Goals:
Test all features (manually + API)


Deploy backend (Render/Railway)


Deploy frontend (Netlify/Vercel)


Record demo video (if required)


Deliverables:
Live project link


GitHub repo with README


Demo walkthrough video



✅ Final Deliverables:
✅ Fully functional deployed web app


✅ GitHub repo with frontend + backend


✅ Figma design file


✅ User authentication


✅ Mood-based movie recommendation system


✅ Optional AI mood detection


✅ Watchlist & ratings


✅ Admin panel


✅ Feedback form


✅ Final report +  demo video

-------conclusion----------
    
