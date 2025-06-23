# DevOps Internship Assignment – Nginx Reverse Proxy with Docker Compose

This project sets up a reverse proxy using **Nginx** in Docker to route traffic to two backend services:

- A **Go (Golang)** application (`service_1`)
- A **Python (Flask)** application (`service_2`)

All services are containerized and orchestrated using **Docker Compose**, accessible via a single port (`localhost:8080`).

---

## 📁 Project Structure

├── docker-compose.yml
├── nginx/
│ ├── nginx.conf
│ └── Dockerfile
├── service_1/
│ ├── Dockerfile
│ └── main.go
├── service_2/
│ ├── Dockerfile
│ ├── main.py
│ └── requirements.txt
└── README.md

---

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

---

### 🔧 Setup Instructions

1. **Clone or extract the repository:**

   ```bash
   git clone https://github.com/van-shika-k/inter.git
   cd  inter
   ```

   Build and run all containers:
   docker-compose up --build

   run :
   Go Service 1: http://localhost:8080/service1/
   Python Service 2: http://localhost:8080/service2/
