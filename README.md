# ☁️ Cloud CI/CD Pipeline & Containerized Web App (`cloud-cicd-gcp-pipeline`)

[![GCP](https://img.shields.io/badge/Cloud-Google_Cloud_Platform-EA4335?style=flat-square&logo=googlecloud)](https://cloud.google.com)
[![Docker](https://img.shields.io/badge/Container-Docker_Multi--Stage-2496ED?style=flat-square&logo=docker)](https://docker.com)
[![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=flat-square&logo=githubactions)](https://github.com/features/actions)
[![Terraform](https://img.shields.io/badge/IaC-Terraform_GCP-7B42BC?style=flat-square&logo=terraform)](https://terraform.io)

End-to-end automated Continuous Integration and Continuous Deployment pipeline built in GitHub Actions, containerized with multi-stage Docker builds, and automatically deployed to Google Cloud Platform Compute Engine with automated rollback on failure.

---

## 🏛️ Pipeline Architecture

```
Code Push -> Unit Tests -> Trivy Security Scan -> Docker BuildKit -> GCP Artifact Registry -> GCP Compute Engine -> Healthcheck Verification
```

---

## 👤 Author
**Piyush Chauhan**  
*DevOps & Cloud Engineer*  
- GitHub: [@pxyushch](https://github.com/pxyushch)  
- Email: [peeyushrajput321@gmail.com](mailto:peeyushrajput321@gmail.com)
