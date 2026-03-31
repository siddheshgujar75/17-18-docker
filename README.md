Docker Nginx Project (Day 17 & 18)

📌 Overview

This project demonstrates the fundamentals of containerization using Docker and remote image management using Docker Hub.

The goal was to:

Build a Docker image for a simple web application

Run and test it locally

Push the image to Docker Hub

Pull and run it on another environment

🧩 Architecture

Local Machine
   ↓
Docker Image (Nginx + HTML)
   ↓
Docker Hub (Remote Repository)
   ↓
Pull & Run Anywhere

📂 Project Structure

docker-nginx-project/
│
├── Dockerfile
└── index.html


🎯 Results
Successfully containerized a static web application
Pushed Docker image to Docker Hub
Verified application portability across environments
Demonstrated real-world DevOps workflow
