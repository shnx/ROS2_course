# ROS 2 Course

> **This repository** contains materials for a hands-on ROS 2 course.  
> Below you’ll find quick, copy-pasteable steps to install **ROS 2** (recommended on **Ubuntu 22.04 / Jammy**) and **Docker** so students can follow along locally or run ROS 2 inside containers.

---

## Table of Contents
1. Overview  
2. Prerequisites  
3. Install ROS 2 (Ubuntu 22.04 — example using **Iron**)  
4. Install Docker (Engine) on Ubuntu  
5. Quick verification (ROS 2 and Docker)  
6. Running ROS 2 in Docker (optional)  
7. Troubleshooting & tips  
8. Useful links & references  

---

## 1 — Overview
This README gives students a reproducible setup to follow the course: local ROS 2 installation for development, plus Docker so you can run examples in containers (useful for avoiding host dependency issues).  
ROS 2 distributions are released regularly — check the ROS docs for the distro corresponding to your Ubuntu version.

---

## 2 — Prerequisites
- Ubuntu **22.04 LTS** (Jammy) recommended for ROS 2 Iron / Humble.  
- Minimum ~10 GB free disk, internet access.  
- A non-root user with `sudo` privileges.  
- Optional: a USB camera or Intel RealSense if you will use sensors later.

---

## 3 — Install ROS 2 (example: Iron / Jammy)

### 1) Locale
```bash
sudo locale-gen en_US en_US.UTF-8
sudo update-locale LC_ALL=en_US.UTF-8 LANG=en_US.UTF-8
export LANG=en_US.UTF-8
