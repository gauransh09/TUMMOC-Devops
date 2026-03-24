# DevOps Demo App

## Features
- CI/CD using GitHub Actions
- Docker containerization
- Terraform for AWS infrastructure
- Monitoring using Prometheus & Grafana

## Run Locally
```bash
docker-compose up -d

Access
App: http://localhost:3000
Prometheus: http://localhost:9090
Grafana: http://localhost:3001

## Terraform

cd terraform
terraform init
terraform apply


---

#  **STEP 9: Push to GitHub**

```bash
git add .
git commit -m "Initial DevOps pipeline setup"
git push origin main
