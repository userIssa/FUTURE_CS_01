# OWASP Juice Shop Security Assessment

## 📌 Overview
This repository documents my **second task** in the **Future Interns Cybersecurity Internship**:  
a **Web Application Security Assessment** of the intentionally vulnerable [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/).

The goal was to simulate a real-world client engagement by identifying vulnerabilities, mapping them to the **OWASP Top 10 (2021)**, and producing a professional **Security Assessment Report** with remediation steps.

---

## 🛠 Tools & Environment
- **Docker** – hosted OWASP Juice Shop locally  
- **Burp Suite Community Edition** – intercepting, analyzing, and manipulating HTTP requests  
- **SecLists** – wordlists for brute-force attacks  
- **Browser DevTools** – static code inspection  
- **Local environment** – screenshots, logs, and documented findings

---

## 🔎 Key Findings
The following vulnerabilities were identified and documented during the assessment:

- SQL Injection leading to admin access  
- Weak account recovery mechanisms (knowledge-based questions)  
- Hidden admin routes exposed in client-side code  
- Insecure Direct Object Reference (IDOR) in basket functionality  
- Backup file disclosure via poison null byte injection  
- Confidential documents accessible via FTP  
- Reflected Cross-Site Scripting (XSS) in the search input  

---

## 📄 Deliverables
- **Security Assessment Report (PDF)** – risk ratings, findings, OWASP Top 10 mapping, remediation steps  
- **Evidence Screenshots** – proof-of-findings captured during testing  
- **Tool Logs** – Burp Suite HTTP history and raw request/response exports  

---

## 🚀 Lessons Learned
- How to approach a web application like an attacker, while thinking like a defender  
- Importance of **secure coding practices** (parameterized queries, input validation, role-based access control)  
- How to structure and present findings in a **client-ready report**  
- Reinforcement of the OWASP Top 10 as a guiding framework  

---

## 🙏 Acknowledgments
Special thanks to **Future Interns** for the opportunity to grow my cybersecurity skills through real-world inspired projects.

---

## 📂 Repository Structure
```plaintext
📁 report/
 ├── JuiceShop-Security-Assessment.pdf     # Final professional report
 ├── Evidence/                             # Screenshots and proof-of-findings
 └── Logs/                                 # Burp Suite exports and request/response files
```

---

## 🔗 References
Check out [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/).

Read the full [OWASP Top 10 (2021)](https://owasp.org/Top10/).

Download [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload).

## 🌟 About

This project is part of my cybersecurity internship portfolio. It demonstrates practical skills in vulnerability assessment, ethical hacking, and professional reporting.
