
# 🚀 DevOps Training - 6 Day Workshop (March 27 – April 3, 2025)

Welcome to the complete documentation of a 6-day hands-on DevOps training program. This repository includes learnings, practical exercises, commands used, and screenshots categorized day-wise.

---

## 📅 Schedule Overview

| Day | Date         | Topics Covered                           |
|-----|--------------|-------------------------------------------|
| 1   | March 27, 2025 | Docker, Kubernetes, Git Bash             |
| 2   | March 28, 2025 | Linux File Permissions, Bash Commands    |
| 3   | March 29, 2025 | Docker Advanced Concepts & Compose       |
| 4   | April 1, 2025 | Kubernetes Deep Dive                     |
| 5   | April 2, 2025 | Jenkins and CI/CD Concepts               |
| 6   | April 3, 2025 | Jenkins Pipeline & End-to-End Workflow   |

---

## 📘 Day 1: Docker, Kubernetes, Git Bash

### 🔹 Docker
- Containerization platform to bundle apps and dependencies.
- **Basic Commands**:
  - `docker build`, `docker run`, `docker ps`, `docker stop`, `docker images`

### 🔹 Kubernetes
- Container orchestration tool to manage clusters.
- **Core Concepts**:
  - Pods, Deployments, Services

### 🔹 Git Bash
- Terminal tool for Windows with Git support.
- **Common Git Commands**:
  - `git init`, `git add`, `git commit`, `git push`, `git pull`, `git status`

---

## 📘 Day 2: Linux File Permissions & Basic Commands

### 🔹 Permissions Structure
- **Read = 4**, **Write = 2**, **Execute = 1**
- Applied to: `User`, `Group`, `Others`
- Example: `chmod 755 file`

### 🔹 File Operations
- `ls` – list contents  
- `cat filename` – display or append to file  
- `nano filename` – edit file with GNU nano  
  - Save with `CTRL + X`, `Y`, `Enter`

---

## 📘 Day 3: Docker Advanced Concepts

### 🔹 Dockerfile
- Script containing instructions to build a Docker image

### 🔹 Docker Compose
- YAML file to run multi-container apps
- Command: `docker-compose up`

### 🔹 Hands-on
- Create custom image using Dockerfile
- Run containers using `docker-compose.yml`

---

## 📘 Day 4: Kubernetes Deep Dive

### 🔹 kubectl (Kubernetes CLI)
- Commands:
  - `kubectl create`
  - `kubectl get pods`
  - `kubectl describe pod`
  - `kubectl delete`

### 🔹 YAML Configurations
- Define pods, services, deployments via `.yaml` files

---

## 📘 Day 5: Jenkins & CI/CD Introduction

### 🔹 Jenkins Overview
- Open-source automation server for CI/CD
- Built using Java

### 🔹 Key Features
- Pipelines (Declarative & Scripted)
- Webhooks for Git integration
- Plugins for Docker, Kubernetes, etc.

---

## 📘 Day 6: Jenkins Pipelines & Final Project

### 🔹 Jenkins Pipeline
- Defined using `Jenkinsfile`
- **Pipeline Stages**: `Build → Test → Deploy`

### 🔹 Final DevOps Workflow
