# API Health Monitoring System

## 📌 Overview

This project is a cloud-based **API Monitoring and Health Check System** designed to automatically track the **uptime, response time, and reliability** of REST APIs. It helps identify failures early, visualize performance trends, and send alerts when APIs go down.

The project is built using **free and open-source tools** and follows real-world software engineering and DevOps practices.

---

## 🎯 Objectives

* Monitor API availability and performance
* Detect failures and high latency
* Store health check results for analysis
* Visualize metrics using dashboards
* Send alerts on critical issues

---

## 🛠️ Tech Stack

* **Backend:** Python (FastAPI)
* **Database:** Supabase (PostgreSQL)
* **Monitoring:** Prometheus
* **Visualization:** Grafana Cloud
* **Hosting:** Render (Free Tier)
* **CI/CD:** GitHub Actions
* **Containerization:** Docker

---

## ⚙️ Features

* Automated API health checks
* Measures response time and status codes
* Uptime and failure tracking
* Prometheus-compatible metrics endpoint
* Grafana dashboards for visualization
* Alerting via Email / Slack
* CI/CD pipeline for automation

---

## 🏗️ Project Architecture

1. APIs are registered in the system
2. Health check service periodically calls APIs
3. Results are stored in PostgreSQL
4. Metrics are exposed to Prometheus
5. Grafana visualizes performance data
6. Alerts are triggered on failures

---

## 🚀 How It Works

* The system sends periodic HTTP requests to registered APIs
* Response status and latency are recorded
* Metrics are updated in real time
* Dashboards display trends and uptime
* Alerts notify when thresholds are breached

---

## 📂 Project Structure

```
api-health-monitor/
│── app/
│   ├── main.py
│   ├── monitor.py
│── prometheus/
│── Dockerfile
│── requirements.txt
│── README.md
```

---

## 🧪 Testing

* Supports testing with public APIs
* Failure scenarios simulated by invalid endpoints
* Metrics and alerts verified using Grafana

---

## 📈 Future Improvements

* Authentication for API access
* Support for HTTPS certificates checks
* Load testing integration
* Custom alert rules per API

---

## 🧠 Skills Demonstrated

* Backend API development
* Cloud deployment
* Observability & monitoring
* CI/CD automation
* System design

---

## 📄 License

This project is open-source and free to use for learning and educational purposes.
