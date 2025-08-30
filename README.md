# CyberSecurity-TeamG3-Project2


# Cross Site Scripting (XSS) - Reflected & Stored XSS

This repository contains a presentation on **Cross Site Scripting (XSS)** vulnerabilities, focusing on **Reflected XSS** and **Stored XSS** demonstrations using DVWA (Damn Vulnerable Web Application).

---

## 📌 Overview
Cross-Site Scripting (XSS) is a common web security vulnerability that allows attackers to inject malicious scripts into web applications. This presentation explains:
- What XSS is
- Types of XSS
- Real examples of Reflected and Stored XSS
- Impacts of XSS attacks
- Mitigation strategies to prevent them

---

## 📂 Contents
- **XSS_Presentation.pptx** → The presentation file  
  - Introduction to XSS  
  - Reflected XSS (Low, Medium, High Security)  
  - Stored XSS (Low, Medium, High Security)  
  - Real payload examples  
  - Security impacts  
  - Mitigation best practices  

---

## 🚀 Topics Covered
### 🔹 Types of XSS
- **Reflected XSS**  
  Executes when malicious input is reflected back immediately in the response.  

- **Stored XSS**  
  Malicious scripts are permanently stored on the server and executed whenever a user visits the infected page.  

- **DOM-based XSS**  
  Execution happens on the client-side due to insecure JavaScript handling.  

### 🔹 Examples
- Reflected (Low):  
  ```html
  <h1>Vivek</h1>
