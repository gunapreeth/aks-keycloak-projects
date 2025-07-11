📌 1. Project Overview

This project demonstrates the deployment of three services on an Azure Kubernetes Service (AKS) cluster:
- **Keycloak** for authentication and authorization
- **PostgreSQL** as the database
- **NGINX** as a static web server

The infrastructure is automated using **Terraform**, configuration is managed using **Ansible**, and the application is deployed on **Kubernetes**. The entire process is automated through a **CI/CD pipeline**.

🚀 2. Technologies & Tools Used

- **Azure Kubernetes Service (AKS)**
- **Terraform** (Infrastructure as Code)
- **Ansible** (Configuration Management)
- **Kubernetes** (Container Orchestration)
- **Docker Images**: Keycloak, Postgres, NGINX
- **CI/CD**: GitHub Actions or GitLab CI/CD

🗂 3. Project Structure

aks-keycloak-postgres-nginx/
├── ansible/          # Ansible playbooks (optional)
├── cicd/             # CI/CD pipeline files (GitHub Actions or GitLab)
├── kubernetes/       # Kubernetes manifests (YAML)
├── terraform/        # Terraform scripts for AKS
└── README.md


🏗 4. Planned Project Workflow (Steps)
1. **Infrastructure Setup**: Create cloud infrastructure using **Terraform** (AKS cluster, networking).
2. **Configuration**: Use **Ansible** to manage configuration .
3. **Kubernetes Deployment**: Deploy Keycloak, PostgreSQL, and NGINX using Kubernetes YAML files.
4. **CI/CD Automation**: Automate the entire build and deployment using **GitHub Actions**.

✅ 5. To-Do List
- [x] Create GitHub repository and README
- [ ] Write Kubernetes YAML files
- [ ] Set up CI/CD pipeline
- [ ] Create Terraform infrastructure code
- [ ] Write Ansible playbooks
- [ ] Deploy to Azure using AKS

🧑💻 6. Author
Your Name (https://github.com/gunapreeth/aks-keycloak-project.git)
