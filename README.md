# terraform-docker

## 🏗️ Infrastructure as Code (IaC) with Terraform

##  Provision Docker Container Using Terraform

This demonstrates **Infrastructure as Code (IaC)** using **Terraform** to provision and manage a local Docker container.

Instead of manually creating a Docker container using Docker commands, Terraform is used to define the desired infrastructure in a configuration file and manage its complete lifecycle.

### Objective

Provision an Nginx Docker container locally using Terraform.

### Tools Used

- Terraform
- Docker
- Nginx
- VS Code

---

## 🔄 Terraform + Docker Architecture

```
                Terraform
                    │
                    │ Docker Provider
                    ▼
              Docker Engine
                    │
                    ▼
              Nginx Image
                    │
                    ▼
            Nginx Container
                    │
                    ▼
             localhost:8080
```
📁 Project Structure
```
terraform-docker/
│
├── .terraform/
├── .terraform.lock.hcl
├── main.tf
├── terraform.tfstate
└── README.md
```
## Terraform Workflow
```
terraform init
       ↓
terraform validate
       ↓
terraform plan
       ↓
terraform apply
       ↓
Verify Docker Container
       ↓
terraform state
       ↓
terraform destroy
```

## SNAPSHOTS
<img width="1621" height="853" alt="Screenshot 2026-10-05 232818" src="https://github.com/user-attachments/assets/c5e8c4c8-48d4-4ace-b161-790390ed1d8f" />

---

<img width="1176" height="268" alt="Screenshot 2026-10-06 001634" src="https://github.com/user-attachments/assets/bdeed69e-2a88-48b5-989c-95960f51bfd1" />

