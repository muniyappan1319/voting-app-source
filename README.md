# Azure DevOps CI/CD with GitOps using Argo CD on AKS

This is a personal DevOps project demonstrating an end-to-end CI/CD pipeline
using Azure DevOps, Docker, Azure Container Registry (ACR),
Azure Kubernetes Service (AKS), and GitOps deployment with Argo CD.

## Project Flow
1. Code commit triggers Azure DevOps CI pipeline
2. Docker image is built and pushed to ACR
3. CD pipeline updates Kubernetes manifests in GitOps repository
4. Argo CD continuously monitors the GitOps repo
5. AKS automatically deploys the latest version

## GitOps Repository
https://github.com/muniyappan1319/voting-app-k8s-manifests

## Tools Used
- Azure DevOps
- Docker
- Azure Container Registry
- Azure Kubernetes Service
- Argo CD
- GitOps
