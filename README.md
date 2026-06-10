🎮 Gaming Platform

A simple Flask-based DevOps project demonstrating CI/CD, containerization, orchestration, and monitoring using modern DevOps tools.

📌 Overview

This project is built to practice and demonstrate core DevOps concepts:

Version Control with Git & GitHub
Continuous Integration using GitHub Actions
Containerization using Docker
Orchestration using Kubernetes
Monitoring using Prometheus & Grafana
⚙️ Tech Stack
Python 🐍
Flask 🌐
Docker 🐳
Kubernetes ☸️
GitHub Actions ⚡
Prometheus 📊
Grafana 📈
🚀 Getting Started
1. Clone the repository
git clone https://github.com/mrudulasakpal2109/gaming-platform
cd gaming-platform
2. Install dependencies
pip install -r requirements.txt
3. Run the application
python app.py

Visit:

http://localhost:5000
🐳 Docker Setup
Build image
docker build -t gaming-platform .
Run container
docker run -p 5000:5000 gaming-platform
🔗 API Endpoints
Endpoint	Method	Description
/	GET	Home page
/health	GET	Health check
/game	GET	Game status
⚡ CI/CD Pipeline (GitHub Actions)

On every push to main branch:

Checkout repository
Setup Python environment
Install dependencies
Run basic checks
Build Docker image
📊 Monitoring
Prometheus → collects metrics (CPU, memory, requests)
Grafana → visual dashboard for monitoring
📁 Project Structure
gaming-platform/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── .github/workflows/ci.yml
├── k8s/
│   └── deployment.yaml
└── README.md
👨‍💻 Author

DevOps Mini Project — Gaming Platform
For learning CI/CD, Docker, Kubernetes & Monitoring

⭐ Future Improvements
Add login system
Add real game logic
Deploy on cloud (AWS / Azure)
Add Helm charts for Kubernetes
