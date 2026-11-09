cat > README.md <<'EOF'
# Infrastructure as Code with Terraform and Docker

## Project Overview

This project demonstrates Infrastructure as Code (IaC) using Terraform and Docker.

Terraform is used to automatically download the Nginx Docker image and provision a Docker container without manually creating it.

## Technologies Used

- Terraform
- Docker
- Nginx
- Ubuntu (WSL)

## Project Architecture

Terraform Configuration (`main.tf`)
        |
        v
Docker Provider
        |
        v
Download Nginx Image
        |
        v
Create Docker Container
        |
        v
Access Nginx on localhost:8081

## Implementation

### 1. Initialize Terraform

```bash
terraform init