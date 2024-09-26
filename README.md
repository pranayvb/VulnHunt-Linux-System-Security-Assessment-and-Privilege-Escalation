# **VulnHunt: Linux System Security Assessment and Privilege Escalation**

This repository contains the project report and related findings for the ENPM695 – Secure Operating System** course at the University of Maryland, taught and supervised by **Prof. Ido Dubrawsky**. Our team, A2DSP, conducted an in-depth vulnerability assessment on a Linux virtual machine to evaluate its security posture and analyze potential security risks.

**Project Team Members**
- Aashrut Pant
- Divye Raghav
- Anmol Chaudhary
- Surya Saketh Korlepara
- Pranay Venkata Bhamidipati

## **Project Overview**

We were provided with a Linux virtual machine, **ENPM695 Project Target System**, which exhibited unusual behavior, prompting us to investigate and uncover any breaches or security issues. The goal of this project was to:

- Conduct a **vulnerability assessment** of the system.
- Identify security breaches and analyze compromised files.
- Recover **encrypted files** and capture the **flag file** hidden by the attacker.

## **Key Findings**

- **User Enumeration**: We successfully enumerated user accounts, leading to root privileges.
- **Service and Port Scanning**: Identified open ports and services, allowing access points into the system.
- **File Discovery**: Located **7 encrypted files** and **1 flag file** stored by the attacker.
  
## **Approach and Methodology**

The team's approach was divided into several key phases:

1. **Reconnaissance**: Scanning the target machine to identify open ports and services.
2. **User Enumeration**: Gaining information about user accounts to escalate privileges.
3. **Privilege Escalation**: Successfully elevating access to root privileges.
4. **File Discovery**: Identifying encrypted files and analyzing them.
5. **Reporting**: Documenting the entire process and results in a detailed technical report.

## **Project Report**

The technical report provides a comprehensive explanation of the approach, tools, and methodologies used throughout the project. It includes:

- A step-by-step guide to the vulnerability assessment process.
- Details on how the team gained root privileges.
- Insights into the identification of encrypted files and the flag.

## **Tools Used**

- **nmap** for port scanning and service enumeration.
- **hydra** for password cracking and user enumeration.
- **john** for decryption and analysis of encrypted files.
- **Linux-based commands** for privilege escalation and system probing.

## **Conclusion**

This project was an excellent hands-on exercise in vulnerability assessment and secure system analysis. We were able to uncover several critical vulnerabilities, gain root privileges, and identify sensitive files stored by an attacker. The findings and procedures are fully documented in the project report.
