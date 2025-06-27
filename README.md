# Docker-Multitier-App

# Dockerized Multi-tier App with Nginx Reverse Proxy

## Objective
Deploy a containerized multi-tier web application using Docker Compose, with Nginx acting as a reverse proxy to route traffic between frontend and backend services.

---

## Tools and Technologies

- Docker  
- Docker Compose  
- Nginx  
- Python (Flask)  
- HTML/CSS (Frontend)  
- Linux Shell / Terminal

---

## Project Structure

Docker-Multitier-App/
├── frontend/
│ ├── Dockerfile # Static frontend container using nginx
│ └── index.html # HTML landing page
├── backend/
│ ├── Dockerfile # Flask backend container
│ └── app.py # Python backend code
├── nginx/
│ └── nginx.conf # Reverse proxy config
├── docker-compose.yml # Compose file for multi-container setup
└── README.md # Project documentation


---

## How to Run This Project Locally

1. **Clone the repository**:

   ```bash
   git clone https://github.com/YOUR_USERNAME/Docker-Multitier-App.git
   cd Docker-Multitier-App
   
Build and start containers using Docker Compose:

docker compose up --build

Open in your browser:

Frontend: http://localhost/frontend

Backend: http://localhost/backend

Stop all services:

docker compose down

Author
Noor Mohammed Maniyar
Email: noormaniyar13@gmail.com
GitHub: https://github.com/noormaniyar07

