# 🧠 AI Smart Revision Scheduler

An AI-powered revision planning system designed to optimize long-term retention for competitive exam aspirants by intelligently scheduling, prioritizing, and automating revision cycles.

This project was **initially developed using Django, Django REST Framework, and SQL-based databases**, and deployed on **Render**.  
It is currently being **modernized and re-architected** using a more performant, cloud-native stack with **FastAPI, Docker, MongoDB, and NGINX**.

---

## 🚀 Key Features

- 📅 **Intelligent Revision Scheduling**  
  Dynamically prioritizes topics based on revision history, frequency, and importance.

- 🤖 **AI-Assisted Content Handling**  
  NLP-based summarization to help learners focus on high-impact revision content.

- ⚙️ **Asynchronous Background Processing**  
  Automated revision reminders and scheduling using background tasks.

- 🌐 **RESTful API Architecture**  
  Clean, modular APIs designed for seamless frontend or client integration.

- ☁️ **Cloud-Native & Scalable Design**  
  Built with scalability, maintainability, and production-readiness in mind.

---

## 🏗️ Tech Stack Evolution

### 🟢 Version 1 – Initial Implementation
- Django  
- Django REST Framework  
- SQL Database  
- Render (Cloud Deployment)

### 🔵 Version 2 – Ongoing Modernization
- FastAPI  
- MongoDB  
- Docker  
- NGINX  
- Render (Production Hosting & CI/CD)

---

## 🔄 System Architecture (Current)

Client (Web / Mobile) 

|

NGINX

|

FastAPI Backend

|

MongoDB

|

Background Workers (Async Tasks)


---

## 🔁 CI/CD & Deployment Workflow

- Source code is managed using **GitHub**.
- The GitHub repository is directly linked to **Render**.
- On every push to the main branch:
  - Render automatically pulls the latest code
  - Builds Docker images
  - Deploys updated services without manual intervention

CI/CD is handled using **Render’s native GitHub integration**, ensuring automated and reliable deployments.

---
## 🧪 API Testing & Developer Experience

- Designed and validated REST APIs using **Postman** for end-to-end testing.
- Created structured **Postman collections** to test authentication, CRUD operations, and edge cases.
- Used environment variables in Postman to simulate multiple deployment environments (local, staging, production).
- Improved API reliability by identifying request/response mismatches and handling error scenarios early in development.

---

## 🛠️ Local Development Setup

```bash
git clone https://github.com/your-username/ai-smart-revision-scheduler.git
cd ai-smart-revision-scheduler
