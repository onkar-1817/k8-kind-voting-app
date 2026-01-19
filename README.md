# 🚀 K8s Kind Voting App

**Author:** Onkar Ghugare

A comprehensive guide to setting up a **Kubernetes cluster using Kind on an AWS EC2 instance**, installing and configuring **Helm**, and deploying a **microservices-based Voting Application** with observability using **Prometheus and Grafana**.

---

## 📌 Overview

This project demonstrates an end-to-end DevOps workflow:

* Launching an AWS EC2 instance
* Installing Docker and Kind
* Creating a Kubernetes cluster using Kind
* Installing and configuring `kubectl`
* Setting up Kubernetes Dashboard
* Installing and configuring Helm
* Deploying applications using Helm
* Monitoring the cluster and application using Prometheus & Grafana

---

## 🧱 Architecture

The application follows a microservices architecture:

* 🗳 **Vote App (Python)** – Front-end web app to vote between two options
* 🧰 **Redis** – In-memory queue to collect votes
* 🔄 **Worker (.NET)** – Processes votes and stores them
* 💾 **PostgreSQL** – Persistent database (Docker volume-backed)
* 📊 **Result App (Node.js)** – Displays voting results in real time

## 📊 Observability

Monitoring is implemented using cloud-native tools:

* **Prometheus** – Metrics collection and scraping
* **Grafana** – Visualization and dashboards

## 📊 Visual Overview

This project includes Kubernetes workloads and monitoring dashboards for the voting application.

Due to system availability constraints, screenshots are not included at this time. Visual artifacts such as Grafana dashboards, Prometheus metrics, and application UI can be easily added later once the environment is accessible.

---

## ⚙️ Tools & Technologies

* **AWS EC2** – Infrastructure hosting
* **Docker** – Containerization
* **Kind** – Kubernetes cluster on EC2
* **Kubernetes Dashboard** – Cluster management UI
* **Helm** – Helm-based application management
* **Helm** – Package manager for Kubernetes
* **Prometheus & Grafana** – Monitoring and observability

---

## 📄 Resume Description

### Project Title

**Deployment and Monitoring of Containerized Applications on AWS EC2 using Kubernetes**

### Description

Implemented and managed a containerized microservices application on AWS EC2 using Kubernetes (Kind). Deployed application components using Kubernetes manifests and Helm charts, and enabled full observability using Prometheus and Grafana. Focused on reliability, scalability, and monitoring of workloads.

### Key Technologies

* AWS EC2 – Infrastructure hosting for Kubernetes clusters
* Kubernetes & Kind – Container orchestration
* Docker – Containerization
* Helm – Kubernetes package management
* Prometheus & Grafana – Monitoring and observability

### Achievements

* Deployed a multi-service voting application on Kubernetes
* Implemented Prometheus and Grafana for real-time monitoring
* Improved visibility into cluster health and application performance
* Achieved stable application performance with scalable Kubernetes workloads

** with scalable and highly available application architecture

---

## 🚀 Future Enhancements

* Add CI/CD pipeline using GitHub Actions or Jenkins
* Configure Ingress with AWS ALB
* Integrate Alertmanager for alerts
* Secure Grafana with authentication

---

## 🙌 Author

**Onkar Ghugare**
DevOps Engineer | Kubernetes | AWS | GitOps (Helm)

LinkedIn & GitHub: @onkar-1817

---

⭐ If you find this project useful, don’t forget to give the repository a star!
