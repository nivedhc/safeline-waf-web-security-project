🔐 Web Application Firewall using SafeLine WAF
📌 Project Overview

This project demonstrates the implementation of a Web Application Firewall (WAF) using SafeLine WAF to protect a vulnerable web application from application-layer attacks.

🎯 Objectives

Deploy SafeLine WAF as a reverse proxy

Demonstrate SQL Injection detection and blocking

Implement HTTP Flood defense with rate limiting

Monitor attack logs in real time

🛠 Tools Used

SafeLine WAF

DVWA (Damn Vulnerable Web Application)

Kali Linux

Ubuntu Server

Apache, PHP, MySQL

🧪 Attacks Demonstrated
1️⃣ SQL Injection

Payload executed successfully without WAF

SafeLine blocked the attack in real time

2️⃣ HTTP Flood Defense

Rate limiting configured

Automatic IP blocking enforced

Logs verified in SafeLine dashboard

🏗 Architecture

Kali Linux (Attacker)
↓
SafeLine WAF (Reverse Proxy + HTTPS)
↓
DVWA (Vulnerable Web App on Ubuntu)

📄 Project Report

The full detailed project report is available in this repository.
