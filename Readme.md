# Task 1: Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)

## Objective

Set up a **CI/CD pipeline** that automatically builds, tests, and deploys a Node.js web application using **GitHub Actions** and **DockerHub**.

---

## Project Overview

This project demonstrates a complete **DevOps workflow**:

1. Code is pushed to GitHub.
2. GitHub Actions automatically:
   - Installs dependencies
   - Runs tests
   - Builds Docker image
   - Logs in to DockerHub
   - Pushes Docker image to DockerHub

The goal is **continuous integration** and **continuous delivery** (CI/CD) automation for a Node.js application.

---

## Tech Stack

- **Node.js** (Backend)
- **Express.js** (Web framework)
- **Docker** (Containerization)
- **GitHub Actions** (CI/CD Automation)
- **DockerHub** (Container Registry)

---

## 🏗 Project Structure

Task1/
├── app.js
├── package.json
├── Dockerfile
└── .github/
└── workflows/
└── main.yml

## Steps I followed

1️ Git Initialization
2️ Node.js App Setup
3️ Dockerization
4️ GitHub Secrets for DockerHub
5️ GitHub Actions Workflow
6️ Trigger CI/CD Pipeline
7️ Verify DockerHub

✅ Outcome

Automated CI/CD pipeline successfully implemented
Node.js app Dockerized and pushed to DockerHub
Entire flow triggered automatically on code push
