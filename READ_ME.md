# 🎮 Gaming Web Application with CI/CD Pipeline

## 📌 Project Overview

This project is a full-stack Gaming Web Application where users can browse board games and reviews. Authenticated users can add games and reviews, while managers have permission to edit and delete reviews.

The application is built using Spring Boot and deployed on AWS EC2 with a complete CI/CD pipeline.

---

## 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring MVC
* JDBC

### Frontend

* HTML5, CSS3, JavaScript
* Thymeleaf
* Bootstrap

### Database

* H2 Database (In-Memory)

### DevOps & Deployment

* Jenkins – CI/CD automation
* Docker – Containerization
* SonarQube – Code quality analysis
* Trivy – Security vulnerability scanning
* AWS EC2 – Cloud deployment

---

## 🔄 CI/CD Pipeline Flow

1. Code pushed to GitHub
2. Jenkins triggers the pipeline
3. Maven builds the application
4. SonarQube checks code quality
5. Trivy scans for vulnerabilities
6. Docker builds the image
7. Application deployed to AWS EC2

---

## 🔐 Features

* Role-based authentication using Spring Security
* Users can add board games and reviews
* Managers can edit and delete reviews
* Secure login system
* CRUD operations
* Responsive UI using Bootstrap

---

## 📁 Project Structure

project/
├── src/
├── tests/
├── Jenkinsfile
├── Dockerfile
├── pom.xml
├── README.md

---

## ▶️ How to Run the Project

```bash
git clone https://github.com/saravanan831509-art/-Gaming-Web-Application-with-CI-CD-Pipeline.git
cd -Gaming-Web-Application-with-CI-CD-Pipeline
mvn clean install
mvn spring-boot:run
```

---

## 🔑 Test Credentials

* User

  * Username: bugs
  * Password: bunny

* Manager

  * Username: daffy
  * Password: duck

---

## 📸 Screenshots



---

## 🚀 Deployment

The application is deployed on AWS EC2 using Docker containers.

---

## 🎯 Key Highlights

* End-to-end CI/CD pipeline implementation
* Secure authentication and role-based access
* Containerized application using Docker
* Cloud deployment on AWS

---

## 💡 Conclusion

This project demonstrates real-world DevOps practices by integrating development, testing, security, and deployment into a single automated pipeline.
