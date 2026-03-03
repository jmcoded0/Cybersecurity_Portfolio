# 🛡️ Johnson Mathew ~ Detection Engineering & Cloud Security Portfolio

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johnson-mathew-150262328/)  
[![Email](https://img.shields.io/badge/-Email-D14836?&style=for-the-badge&logo=gmail&logoColor=white)](mailto:johnsonmatthewayobami@gmail.com)

> Detection Engineer specializing in **SOC Operations, Cloud Security, Threat Detection, and Automated Incident Response**. Delivered **30+ hands-on projects**, including **enterprise-scale simulations** from **Bincom Academy Cybersecurity Intensive** (completed Jan 2026), focusing on **measurable detection coverage**, **reduced response times**, and **proactive automation**. 🚀

---

## 📑 Table of Contents

- [About](#about)  
- [Featured Projects](#featured-projects)  
- [Specialized Labs](#specialized-labs)  
- [Technical Stack](#technical-stack)  
- [Detection Engineering Methodology](#detection-engineering-methodology)  
- [Certifications](#certifications)  
- [Contact](#contact)  

---

## 👤 About

I build resilient **detection pipelines** and secure **cloud environments** through realistic attack simulations, **SIEM engineering**, and **automation**. My work emphasizes **quantifiable outcomes** like **faster threat detection**, **automated remediations**, and **high-fidelity alerting**—aligned with **MITRE ATT&CK** and **NIST CSF**.

**Key Highlights**:  
- Completed **Bincom Academy Cybersecurity Intensive** (Jan 2026): network fundamentals, vuln exploitation, web/endpoint defense, SIEM monitoring, cloud IAM, CTF, and full enterprise capstone.  
- Engineered **30+ projects** demonstrating end-to-end detection engineering in **AWS, GCP, Splunk, Zeek/Suricata, and honeypots**.  
- Achieved simulated reductions in **detection/response times** (**<10 min MTTD/MTTR**) and automated mitigations for common threats.  
- Produced actionable **reports, dashboards, and playbooks** for scalable SOC operations.  

*Last updated: March 2026* ✅

---

## ⭐ Featured Projects

These top projects highlight **full lifecycle detection engineering**: simulate → detect → respond → automate.

### 🏆 [Bincom Academy Final Practical Test – Enterprise Security Simulation](https://github.com/jmcoded0/bincom-final-security-simulation)  
Capstone from Bincom Academy Cybersecurity Intensive (Jan 2026). Built and defended a **small-scale enterprise environment** under structured testing.

**Key Achievements**:  
- Deployed **DVWA web app + Cowrie honeypot** in segmented VMs with centralized logging to **Security Onion / ELK Stack**.  
- Executed **multi-vector attacks**: Nmap recon, Metasploit exploits, brute-force; captured **IOCs** and Wireshark traffic.  
- Implemented defenses: **ModSecurity WAF rules**, firewall policies, service hardening; re-tested to validate **100% mitigation** of simulated exploits.  
- Engineered **SIEM dashboards** for real-time correlations across **port scans, web attacks, brute-force, and multi-source logs**.  
- Delivered professional artifacts: **network diagram, attack/defense screenshots, security logs/dashboards, full incident report with RCA**.

**Impact**: Demonstrated **full SOC lifecycle**; achieved **rapid detection (<5 min)** and effective containment in tests.  
**Technologies**: DVWA, Cowrie, Security Onion, ELK Stack, Nmap, Metasploit, ModSecurity, Wireshark, Linux.  
**Tags**: **Enterprise Simulation**, **SOC Operations**, **Threat Detection**, **Incident Response** ✅

---

### ☁️ [AWS Cloud SOC Simulation – Detection, Attack Emulation & Automated Response](https://github.com/jmcoded0/AWS-Cloud-SOC-Simulation-Detection-Attack-Emulation-Incident-Response)  
End-to-end **cloud-native SOC pipeline** simulating adversary tactics with **automated remediation**.

**Key Achievements**:  
- Deployed **AWS environment** with **CloudTrail ingestion, IAM logging**, and **Terraform IaC** for repeatable setup.  
- Emulated threats: **IAM privilege escalation, misconfigurations, lateral movement**.  
- Engineered **Splunk detection rules and dashboards** for real-time alerts (e.g., unusual API calls, escalation attempts).  
- Automated containment via **AWS Lambda functions** (e.g., revoke excessive permissions, isolate resources).  
- Documented repeatable **incident playbooks and response timelines**.

**Impact**: Reduced simulated incident containment by **~50%**; achieved **<10 min MTTD** for privilege escalations.  
**Technologies**: AWS (EC2, IAM, CloudTrail, Lambda), Splunk, Terraform, Boto3, Python.  
**Tags**: **Cloud SOC**, **Detection Engineering**, **Automation** ☁️

---

### 🛡️ [Production-Grade Cloud Honeypot & Threat Intelligence Pipeline](https://github.com/jmcoded0/Production-Grade-Cloud-Honeypot-Threat-Intelligence-Pipeline)  
Deployed **deceptive honeypot** to capture attacker TTPs and generate actionable intelligence.

**Key Achievements**:  
- Launched **Cowrie honeypot** in AWS with secure forwarding of attacker logs to **Splunk**.  
- Built dashboards visualizing attacker behaviors: login attempts, commands executed, session durations.  
- Analyzed captured data to map **TTPs** and produce **threat intelligence reports**.  
- Integrated alerts for **high-risk patterns** to enable proactive defenses.

**Impact**: Captured and visualized **100+ simulated attacker sessions**; enabled early warning for similar TTPs in near-real-time.  
**Technologies**: Cowrie, Splunk, AWS, Python.  
**Tags**: **Honeypots**, **Threat Intelligence**, **Deception** 🕵️‍♂️

---

### 🔍 [Network Threat Visibility with Zeek, Suricata & Splunk](https://github.com/jmcoded0/Network-Threat-Visibility-with-Zeek-Suricata-Splunk)  
Integrated **network IDS telemetry** for comprehensive threat detection and visualization.

**Key Achievements**:  
- Configured **Zeek and Suricata** for protocol analysis, file extraction, and signature detection.  
- Ingested logs into **Splunk**; created correlation searches and dashboards for anomalies.  
- Simulated intrusions and validated detections.  
- Documented **IOCs** and mitigation recommendations.

**Impact**: Achieved **real-time visibility**; detected brute-force and C2 patterns with **<5 min latency**.  
**Technologies**: Zeek, Suricata, Splunk, Linux, Wireshark.  
**Tags**: **Network Security**, **SIEM**, **IDS/IPS** 🔍

---

### 🧠 [Malware Analysis & Reverse Engineering Lab](https://github.com/jmcoded0/Malware-Analysis-and-Reverse-Engineering)  
In-depth **static/dynamic malware analysis** in controlled sandbox.

**Key Achievements**:  
- Analyzed ransomware/keylogger emulators using sandbox tools.  
- Behavioral monitoring (Procmon), network capture (Wireshark), code disassembly (Ghidra).  
- Extracted **IOCs** (hashes, C2 domains, file artifacts); documented persistence mechanisms.  
- Recommended containment and remediation strategies.

**Impact**: Fully dissected malware; identified **10+ IOCs per sample** and proposed mitigations reducing infection risk.  
**Technologies**: Kali Linux, Ghidra, Wireshark, Procmon, Sysinternals.  
**Tags**: **Malware Analysis**, **Reverse Engineering** 💀

---

## 🛠 Specialized Labs

### Bincom Academy Labs (Jan 2026)
- [bincom-final-security-simulation](https://github.com/jmcoded0/bincom-final-security-simulation) – Capstone  
- [bincom-cybersecurity-honeypot-lab](https://github.com/jmcoded0/bincom-cybersecurity-honeypot-lab)  
- [Bincom-web-application-attack-and-defense-lab](https://github.com/jmcoded0/Bincom-web-application-attack-and-defense-lab)  
- [bincom-vulnerability-scan-exploit-lab](https://github.com/jmcoded0/bincom-vulnerability-scan-exploit-lab)  
- [bincom-cloud-privilege-escalation-lab](https://github.com/jmcoded0/bincom-cloud-privilege-escalation-lab)  

### Cloud Security & Automation
- [AWS-IAM-Privilege-Escalation-Detection](https://github.com/jmcoded0/AWS-IAM-Privilege-Escalation-Detection)  
- [AWS-S3-Serverless-Auto-Remediation-for-Public-Access](https://github.com/jmcoded0/AWS-S3-Serverless-Auto-Remediation-for-Public-Access)  
- [Terraform-Boto3-AWS-Cloud-Automation](https://github.com/jmcoded0/Terraform-Boto3-AWS-Cloud-Automation)  
- [Automating-Cloud-Compliance-Checks-with-Terraform-AWS-Security-Hub](https://github.com/jmcoded0/Automating-Cloud-Compliance-Checks-with-Terraform-AWS-Security-Hub)  
- [GCP-Attack-Response-and-Recovery](https://github.com/jmcoded0/GCP-Attack-Response-and-Recovery)  

### SOC, Monitoring & Detection
- [Splunk-for-Log-Analysis-Threat-Detection](https://github.com/jmcoded0/Splunk-for-Log-Analysis-Threat-Detection)  
- [Phishing-Detection-Simulation-with-Kali-Linux-Splunk](https://github.com/jmcoded0/Phishing-Detection-Simulation-with-Kali-Linux-Splunk)  
- [Real-Time-Network-Monitoring-with-IDS-Tools](https://github.com/jmcoded0/Real-Time-Network-Monitoring-with-IDS-Tools)  
- [mini-soar-playbook](https://github.com/jmcoded0/mini-soar-playbook)  
- [Incident-handler-journal](https://github.com/jmcoded0/Incident-handler-journal)  

### Governance, Analysis & Reporting
- [Web-App-Pentesting-Vulnerability-Management](https://github.com/jmcoded0/Web-App-Pentesting-Vulnerability-Management)  
- [Cybersecurity-Framework-Mapping-Projects](https://github.com/jmcoded0/Cybersecurity-Framework-Mapping-Projects)  
- [Security-Audit](https://github.com/jmcoded0/Security-Audit)  
- [Vulnerability-assessment-report](https://github.com/jmcoded0/Vulnerability-assessment-report)  
- [Network-Incident-Analysis](https://github.com/jmcoded0/Network-Incident-Analysis)  

---

## 🧰 Technical Stack

| Category              | Tools & Skills                                      |
|-----------------------|-----------------------------------------------------|
| **Cloud**             | AWS (EC2, S3, IAM, Lambda, CloudTrail, Security Hub), GCP |
| **SIEM & Monitoring** | Splunk, Security Onion, ELK Stack                   |
| **Network & Detection**| Zeek, Suricata, Wireshark, Nmap, Sysinternals      |
| **Offensive & Analysis**| Metasploit, Burp Suite, Ghidra, Kali Linux         |
| **Automation**        | Python, Bash, Terraform, Boto3, Git, SQL            |

---

## 🧠 Detection Engineering Methodology

1. **Simulate** – Emulate real TTPs (Nmap, Metasploit, IAM abuse).  
2. **Collect** – Aggregate **cloud, network, endpoint telemetry**.  
3. **Detect** – Engineer **high-fidelity SIEM rules/dashboards**.  
4. **Investigate** – Correlate **IOCs** and analyze artifacts.  
5. **Respond** – Execute **automated playbooks/containment**.  
6. **Automate** – Deploy **guardrails for proactive remediation**.

*Example*: Bincom capstone achieved **<5 min detection** of correlated exploits via multi-source SIEM. ✅

---

## 📜 Certifications

- **Bincom Academy Cybersecurity Program Completion – Jan 2026**  
- **ISC2 Certified in Cybersecurity (CC)**  
- **Google Cybersecurity Certificate**  
- **Google Cloud Professional Security Engineer**  
- **AWS Certified Cloud Practitioner**  

---

## 📬 Contact

**Email**: johnsonmatthewayobami@gmail.com  
**LinkedIn**: [Johnson Mathew](https://www.linkedin.com/in/johnson-mathew-150262328)  
**GitHub**: [jmcoded0](https://github.com/jmcoded0)  

Open to **Detection Engineering, SOC Analyst, or Cloud Security roles** 🚀
