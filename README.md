# DevOps CI/CD Pipeline Project
## Problem Statement
This project demonstrates how to implement a complete DevOps pipeline using GitHub Actions. 
The goal is to automate the process of building, testing, and deploying an application 
to ensure faster and reliable software delivery.
## Architecture Diagram
![Architecture](docs/architecture.png)
## CI/CD Pipeline
The pipeline is implemented using GitHub Actions and consists of three stages:

1. Build:
- Installs dependencies
- Prepares the project

2. Test:
- Runs basic tests to verify functionality

3. Deploy:
- Automatically deploys the application to Render when code is pushed to main branch
## Git Workflow
- Created feature branch: feature/devops-enhancement
- Made multiple commits
- Created pull request (PR)
- Merged into main branch after review
## Tools Used
- Git & GitHub
- GitHub Actions
- Docker (optional)
- :contentReference[oaicite:0]{index=0} (for deployment)
## Challenges Faced
- Understanding GitHub Actions workflow syntax
- Fixing deployment errors
- Managing environment variables using GitHub Secrets
