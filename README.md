# Generic-Infrastructure-Framework


## Overview
The Generic Infrastructure Framework is a **Terraform-based reusable framework** designed to provision **Azure cloud infrastructure** in a **consistent, scalable, and secure** manner across multiple environments such as **Development, QA, and Production**.

This framework follows **Infrastructure as Code (IaC)** best practices and uses a **modular architecture** to ensure maintainability and reusability.

---

## Key Features
- Reusable and modular Terraform code
- Multi-environment support (Dev / QA / Prod)
- Environment-specific configurations
- Scalable and maintainable design
- Production-ready folder structure

---

## Technology Stack
- Terraform (>= 1.x)
- Azure (azurerm provider)
- Azure CLI
- Git & GitHub

---

## Repository Structure
```text
Generic-Infrastructure-Framework/
│
├── modules/
│   ├── network/
│   ├── compute/
│   ├── storage/
│   └── security/
│
├── Environment/
│   ├── Dev/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   └── terraform.tfvars
│   │
│   └── Prod/
│       ├── main.tf
│       ├── variables.tf
│       └── terraform.tfvars
│
├── .gitignore
└── README.md
