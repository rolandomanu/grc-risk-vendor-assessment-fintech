## Final Report
[Download Full Risk Assessment Report](docs/Rolando_Huayamave_Vendor_Risk_Assessment.pdf)

## Assumptions
- Vendor operates in AWS cloud environment
- Sensitive customer data (PII) is processed and stored
- APIs are exposed externally for integration

## Business Impact
Failure to address these risks could result in:

- Data breaches affecting customer trust
- Regulatory penalties and compliance violations
- Financial losses due to ransomware attacks
- Service disruption in critical systems
- 
# Vendor Risk Assessment – Fintech Environment

## Overview
This project simulates a real-world third-party (vendor) risk assessment in a fintech environment, focusing on a cloud-based SaaS provider handling sensitive customer data (PII), authentication systems, and critical infrastructure.

The objective is to identify, assess, and mitigate cybersecurity risks associated with external vendors.

---

## Business Problem
Organizations rely heavily on third-party vendors, increasing exposure to risks such as data breaches, unauthorized access, and cloud misconfigurations.

This assessment evaluates how inadequate controls in a vendor environment can impact confidentiality, integrity, and availability of critical systems.

---

## Methodology
- Asset Identification  
- Risk & Threat Analysis  
- Vulnerability Assessment  
- Control Design (Preventive, Detective, Corrective)  
- Gap Analysis  
- Control Mapping to frameworks  

---

## Key Risks Identified
- Data Breach (Customer Data)  
- Unauthorized Access (Credentials)  
- Cloud Misconfiguration  
- Insider Threat (Vendor)  
- Man-in-the-Middle (API Integrations)  
- Ransomware (Backups)  

---

## Controls Implemented
- Multi-Factor Authentication (MFA)  
- SIEM Monitoring & Alerting  
- IAM & Least Privilege  
- Privileged Access Management (PAM)  
- Cloud Security Posture Management (CSPM)  
- TLS 1.2+ Enforcement  
- Immutable Backups  

---

## Gap Analysis Highlights
Critical security gaps identified include:

- Lack of MFA enforcement  
- Absence of real-time monitoring (SIEM)  
- Overly permissive access controls  
- Missing cloud security posture management  
- Weak encryption configurations  
- Lack of backup immutability  

---

## Framework Alignment
This project aligns controls with:

- NIST Cybersecurity Framework  
- ISO/IEC 27001  

---

## Project Structure


---

## Outcome
This assessment demonstrates the ability to:

- Identify and evaluate vendor risks  
- Design effective security controls  
- Perform gap analysis  
- Align controls with industry frameworks  

---

## Author
Rolando M. Huayamave Torres  
GRC Analyst | Risk & Compliance | ISO 27001
