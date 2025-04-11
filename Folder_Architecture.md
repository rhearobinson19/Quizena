# Project Folder Architecture

This file shows a brief architecture diagram of our project folder structure for better understanding. The project follows a modular full-stack architecture, designed for scalability, maintainability, and real-time communication. Below is an overview of the folder structure and the roles of different components.

---

## 📁 Frontend Folder Structure
![](https://github.com/rhearobinson19/Quizena/blob/master/Images/Frontend_arch.jpeg)

<br>
<br>

## 📁 Backend Folder Structure
![](https://github.com/rhearobinson19/Quizena/blob/master/Images/backend_arc.jpeg)

<br>
<br>


## 📁 SRE Folder Structure
![](https://github.com/rhearobinson19/Quizena/blob/master/Images/sre_arch.jpeg)

<br>
<br>


---

## 🔄 Flow Overview

1. **Frontend (React + Vite)**  
   - Users interact with the app via components and views.  
   - React Router manages navigation and protected routes.  
   - Axios is used to make secure API requests to the backend.

2. **Backend (Node.js + Express + Socket.IO)**  
   - Express handles REST API endpoints.  
   - JWT is used for authentication & protected routing.  
   - Socket.IO enables real-time quiz communication between players.

3. **Database (Supabase - PostgreSQL)**  
   - Stores users, quiz questions, scores, and leaderboard info.  
   - Accessed securely using the `postgres` library and .env credentials.

4. **DevOps / Monitoring (SRE folder)**  
   - Docker + Docker Compose containerizes the app.  
   - Prometheus + Grafana for live monitoring.  
   - Loki for centralized logging.

---

## Highlights

-  **Modular Architecture** – Clear separation of concerns
-  **Socket.IO** – Enables multiplayer quiz play
-  **JWT & Protected Routes** – For secure login and gameplay
-  **Supabase DB Integration** – Fast and developer-friendly
-  **Dockerized Setup** – Consistent environment across systems
-  **Prometheus + Grafana** – Powerful observability stack

---

This structure made collaboration seamless and ensured that the app scaled well with feature additions. 


