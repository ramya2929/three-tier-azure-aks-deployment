# Three-Tier Web Application Deployment on Azure Kubernetes Service (AKS)

## Project Overview

Implemented a three-tier web application deployment workflow on Microsoft Azure using React.js, Node.js, Express.js, and MongoDB. Used Docker for containerization, Azure Container Registry (ACR) for storing container images, Azure Kubernetes Service (AKS) for container orchestration, and Azure DevOps Pipelines for deployment workflows.

## Project Repositories

- *Frontend:* [ https://github.com/ramya2929/frontend.git ]
- *Backend:* [ https://github.com/ramya2929/backend.git ]
- *Database:* [ https://github.com/ramya2929/database.git ]


## Architecture

GitHub Repositories
(Frontend | Backend | Database)
             |
             v
  Azure DevOps Pipelines
             |
             v
 Self-Hosted Agent (Azure VM)
             |
             v
       Docker Images
             |
             v
 Azure Container Registry (ACR)
             |
             v
 Azure Kubernetes Service (AKS)
             |
             v
 Kubernetes Deployments & Services
             |
             v
    Three-Tier Application
(React.js | Node.js | MongoDB)


## Technologies Used

- *Cloud Platform:* Microsoft Azure
- *Frontend:* React.js
- *Backend:* Node.js
- *Database:* MongoDB
- *Containerization:* Docker
- *Container Registry:* Azure Container Registry (ACR)
- *Container Orchestration:* Azure Kubernetes Service (AKS)
- *CI/CD:* Azure DevOps Pipelines
- *Version Control:* Git and GitHub
- *Deployment Configuration:* Kubernetes YAML Manifests
- *Cluster Management:* kubectl

## Key Implementation Details

- Organized frontend, backend, and database components into three separate GitHub repositories.
- Worked with Azure DevOps Pipelines for application deployment workflows.
- Configured a self-hosted Azure DevOps agent on an Azure virtual machine.
- Built Docker images using Dockerfiles and pushed images to Azure Container Registry.
- Connected to the AKS cluster using kubectl and kubeconfig.
- Created a Kubernetes namespace named three-tier.
- Used Kubernetes Deployment and Service manifests to configure application components.
- Troubleshot ImagePullBackOff errors caused by missing authentication to the private Azure Container Registry.
- Created a Kubernetes registry Secret named acr-creds and configured imagePullSecrets to enable authenticated image pulls from ACR.

## Key Skills

Microsoft Azure, Azure DevOps, Azure Pipelines, Azure Kubernetes Service (AKS), Azure Container Registry (ACR), Docker, Kubernetes, Git, GitHub, YAML, CI/CD, and Troubleshooting.

## Learning Outcomes

Gained practical experience in cloud application deployment, Docker containerization, Azure DevOps pipeline workflows, Kubernetes orchestration, private container registry authentication, and deployment troubleshooting.
