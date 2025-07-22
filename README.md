# FUTURE_CS_01 – Web Application Security Testing 🔐

This repository contains Task 1 for my Cyber Security Internship with [Future Interns](https://futureinterns.com).  
The objective of this task is to identify and report common web application vulnerabilities.

## 🔍 Task Objective
Perform security testing on a vulnerable web application to identify:
- SQL Injection
- Cross Site Scripting (XSS)
- Authentication Flaws

## 🛠 Tools Used
- Manual testing via web browser
- Target: [OWASP Juice Shop](https://demo.owasp-juice.shop)

## ✅ Vulnerabilities Tested

### 1. SQL Injection
- **Payload Used:** `' OR 1=1--`
- **Result:** Login bypass successful
- **Screenshot:** `sqli_screenshot.png`

### 2. XSS (Cross Site Scripting)
- **Payload Used:** `<script>alert("XSS")</script>`
- **Result:** Attempted via Feedback form
- **Screenshot:** `xss_screenshot.png`

### 3. Authentication Flaws
- **Tested With:** Default/breached credentials (`admin@juice-sh.op`)
- **Result:** Successful login triggered Google warning
- **Screenshot:** `auth_flaw_screenshot.png`

## 📄 Report
See [`Security_Report_Task1.md`](./Security_Report_Task1.md) for full details.

---

## 🌐 Connect with Me
- 🔗 [LinkedIn](https://www.linkedin.com/in/lokeshindala)
- 📫 lokeshindala@gmail.com

