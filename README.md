# Ubuntu Server Portfolio

## Overview

This project is a Linux server portfolio built on Ubuntu Server.

The environment was created using Docker, Nginx, PHP, and MySQL to build a user management web application with authentication.

The goal of this project is to learn Linux server administration, container technology, web server configuration, and basic web application deployment.

---

## Features

- User Login Authentication
- Logout Function
- Session Authentication
- Password Hashing
- User Management (CRUD)
- Access Control
- Docker Container Environment
- Nginx Web Server
- PHP Application
- MySQL Database

---

## Tech Stack

- Ubuntu Server 26.04 LTS
- Docker
- Docker Compose
- Nginx
- PHP
- MySQL
- Git

---

## Project Structure

```text
ubuntu-server-portfolio/
├── README.md
├── compose.yaml
├── html/
│   ├── index.html
│   ├── login.php
│   ├── logout.php
│   ├── home.php
│   ├── show_users.php
│   ├── add_user.php
│   ├── edit_user.php
│   ├── delete_user.php
│   ├── connect.php
│   ├── create_table.php
│   └── info.php
└── nginx/
    └── default.conf
```

---

## Architecture

```text
Browser
    │
    ▼
Nginx (Docker)
    │
    ▼
PHP
    │
    ▼
MySQL
```

---

## Environment

### Host OS
- Windows 11

### Virtual Machine
- VirtualBox

### Guest OS
- Ubuntu Server 26.04 LTS

### Container
- Docker
- Docker Compose

### Web Server
- Nginx

### Programming Language
- PHP

### Database
- MySQL

---

## Completed

- Ubuntu Server Installation
- Git Installation
- Docker Installation
- Docker Compose Configuration
- Nginx Configuration
- PHP Environment
- MySQL Environment
- User Management (CRUD)
- Login Authentication
- Session Authentication
- Password Hashing
- Access Control
- Logout Function

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/sss8283/ubuntu-server-portfolio.git
```

### Move to Project Directory

```bash
cd ubuntu-server-portfolio
```

### Start Docker Containers

```bash
docker compose up -d
```

### Open in Browser

```text
http://localhost
```

---

## Learning Goals

This project was created to learn:

- Linux Server Administration
- Docker & Docker Compose
- Nginx Configuration
- PHP Development
- MySQL Database Management
- Authentication and Session Management
- Git & GitHub Workflow

---

## Future Plans

- Fix UTF-8 (Japanese Encoding)
- Build an Incident Response Practice Lab
- Deploy to AWS
- Configure SSL (HTTPS)
- Learn Linux Server Security
- Improve Monitoring and Logging

---

## Purpose

This project was created to improve practical Linux server administration skills and build a portfolio for an entry-level Linux Server Engineer position.
