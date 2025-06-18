# 🛡️ Maven Clinic Network Intrusion - Cybersecurity Incident Report

## 📄 Project Overview

This project contains a detailed cybersecurity incident report analyzing a simulated network intrusion at **Maven Clinic**, prepared as part of a cybersecurity mini-sprint. The report covers the identification, investigation, containment, and future mitigation strategies following the discovery of suspicious activity across internal systems.

## 🧠 Skills & Tools Demonstrated

- SIEM Analysis (Windows Event Logs, Firewall Logs)
- Threat Investigation (VirusTotal, Angry IP Scanner, DNS Blacklist Checkers)
- Log Review & Forensics
- Incident Response using the **NIST Framework**
- Network Security & Access Control
- Short-term & Long-term Containment Planning
- Vulnerability Identification
- Stakeholder Communication & Recommendations

## 🕵️ Incident Summary

- **Date Detected:** September 20, 2023
- **Systems Affected:** DESKTOP-1234567, SERVER-12345, SQLSERVER-12345, DC-SERVER-01
- **Key Events:**  
  - Brute-force login attempts from suspicious internal IPs  
  - Successful unauthorized login to admin account  
  - Firewall and policy change alerts  
  - SQL Server I/O errors indicating potential tampering  

## 🚨 Key Findings

- **Compromised Admin Account:** Repeated failed login attempts followed by a success  
- **Firewall Alerts:** Unusual activity on ports 22 (SSH) and 445 (SMB)  
- **SQL Server Integrity Risk:** I/O error detected, suggesting potential compromise  
- **Unknown Application Activity:** Suspicious inbound connection attempts from unrecognized IPs  

## 🛡️ Response Actions

### 🔧 Short-Term:
- Isolated affected systems
- Blocked suspicious IPs
- Disabled compromised user accounts
- Preserved forensic evidence

### 🧱 Long-Term:
- Applied patches and updated all systems
- Enhanced firewall rules
- Deployed IDS/IPS systems
- Enforced MFA and least privilege access
- Scheduled regular security audits

## 📊 Recommendations

- **Implement MFA across all systems**
- **Improve log monitoring and alerting**
- **Develop robust network segmentation**
- **Introduce PAM (Privileged Access Management)**
- **Conduct regular security awareness training**
- **Perform penetration tests and vulnerability scans**

## 💰 Estimated Security Improvement Costs

| Initiative                          | Estimated Cost       |
|------------------------------------|----------------------|
| Multi-factor Authentication (MFA)  | $15,000 – $25,000    |
| SIEM Monitoring Upgrade            | $30,000 – $50,000    |
| Security Training                  | $10,000 – $15,000    |
| Network Segmentation               | $50,000 – $100,000   |
| PAM Solution                       | $75,000 – $150,000   |
| Continuous Security Program        | $100,000 – $200,000 annually |


## 🙋 About the Author

**Likith Sai Kuruhuri**    
📫 [likithsaikuruhuri1@gmail.com](mailto:likithsaikuruhuri1@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/kuruhurilikithsai)

---

> 📝 *This project is for educational and portfolio purposes. No real patient or clinic data was involved.*
