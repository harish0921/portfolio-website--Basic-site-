# CI/CD Pipeline Project - HTML Static Web App

A simple static website built with HTML and CSS, containerized with Docker, and deployed via Jenkins in a CI/CD pipeline.

## Project Highlights
- HTML/CSS static web app
- Docker containerization
- Jenkins automation (CI/CD)
- GitHub integration

## Run Locally
```bash
docker build -t devops-static-site .
docker run -p 8080:80 devops-static-site
