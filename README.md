# Simple-App-development-with-Ansible
# 🚀 Flask App Deployment with Docker, Ansible & Kubernetes

A simple Python Flask web application that is containerized using Docker and deployed to a Kubernetes cluster using Ansible automation.

---

## 📦 Project Structure

flask-k8s-project/
├── app/
│ ├── app.py # Flask application
│ ├── Dockerfile # Docker build file
├── ansible/
│ ├── inventory # Ansible inventory file (with your Kubernetes node IP)
│ ├── build-image.yml # Ansible playbook to build and push Docker image
│ ├── deploy-to-k8s.yml # Ansible playbook to deploy app to Kubernetes
├── k8s/
│ ├── deployment.yml # Kubernetes Deployment manifest
│ ├── service.yml # Kubernetes Service manifest
├── requirements.txt # Python dependencies
├── README.md


---

## 🧪 Technologies Used

- **Python (Flask)** – Lightweight web app framework
- **Docker** – Containerization
- **DockerHub** – Image repository
- **Ansible** – Automation tool for infrastructure and app deployment
- **Kubernetes (Minikube)** – Container orchestration
- **kubectl** – Command-line tool to interact with Kubernetes

---

## ✅ Prerequisites

- Docker installed and configured
- Minikube Kubernetes cluster up and running
- Ansible installed
- Python 3.9+
- DockerHub account
- SSH access to your Kubernetes node (for Ansible)
- `kubectl` configured to access your Minikube cluster

---
