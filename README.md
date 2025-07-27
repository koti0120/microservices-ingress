# 🚀 Deployment of Microservices Application using Ingress Controller


![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)


```
✅ What is an Ingress Controller in Kubernetes?
An Ingress Controller is a Kubernetes component that helps manage how external users access services inside the cluster.

In Kubernetes, we create Ingress objects to define routing rules — for example, if a user visits /home, it should go to the home service.

The Ingress Controller watches these rules and sets up a reverse proxy (like NGINX, Traefik, or HAProxy) to route the traffic correctly.

🔁 Types of Routing
1. Port-Based Routing

123.456.78.99:81 → Home Page

123.456.78.99:82 → Movies Page

123.456.78.99:83 → Songs Page

👉 This is harder to manage and not user-friendly.

2. Path-Based Routing using Ingress

example.com/home

example.com/movies

example.com/songs

👉 This is cleaner and easier to manage.

📌 Types of Ingress Controllers:

 ➤ NGINX Ingress Controller

 ➤ AWS ALB Ingress Controller

 ➤ Traefik

 ➤ HAProxy

 ➤ Istio Gateway

💡 Benefits of Using an Ingress Controller:

 ➤ Reduces cost by avoiding multiple LoadBalancers

 ➤ Easy to manage routing with path and host rules

 ➤ Handles SSL/TLS certificates for secure HTTPS

 ➤ Centralized access control and traffic management

 ➤ Supports autoscaling and load balancing

Makes the cluster setup more efficient and user-friendly

```
## 🛠️ Project Overview

This project demonstrates a production-grade deployment of a multi-page web application on **AWS EKS** with **Ingress Controller** using a complete **Jenkins CI/CD** pipeline.

## 🔧 Tools Used

| Category        | Tools                                                                                      |
|-----------------|-------------------------------------------------------------------------------------------|
| Version Control | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white) |
| CI/CD           | ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=flat&logo=jenkins&logoColor=white) |
| Containers      | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white) |
| Orchestration   | ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=flat&logo=kubernetes&logoColor=white) ![AWS EKS](https://img.shields.io/badge/AWS_EKS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white) |
| Monitoring      | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=Prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=flat&logo=grafana&logoColor=white) |
| GitOps          | ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white) |

