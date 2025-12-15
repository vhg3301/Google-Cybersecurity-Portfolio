# Security Audit Checklist - Botium Toys

## 📋 Project Overview
This is my first project from the Google Cybersecurity Professional Certificate on Coursera. The project involves conducting an internal security audit for Botium Toys, a fictional toy company, to identify security risks and compliance gaps.

## 🎯 Objective
Perform a comprehensive internal security audit by evaluating:
- Current security controls implementation
- Compliance with industry regulations (PCI DSS, GDPR, SOC)
- Risk assessment based on existing vulnerabilities
- Recommendations for security posture improvement

## 🏢 Company Profile: Botium Toys

**Industry:** Retail (Toys - Physical store and e-commerce)

**Assets managed by IT Department:**
- On-premises equipment and employee devices
- E-commerce platform and physical storefront
- Customer data and payment processing systems
- Internal network and databases
- Legacy systems requiring manual monitoring

**Current Risk Score:** 8/10 (High) - Due to lack of proper controls and incomplete compliance adherence

## 🔍 Audit Scope
The audit covers the **entire security program** at Botium Toys, including:
- All physical and digital assets
- Internal processes and procedures
- Controls implementation (Administrative, Technical, Physical)
- Compliance with PCI DSS, GDPR, and SOC standards

## 📝 Methodology
The audit evaluates security controls across three categories:

1. **Administrative/Managerial Controls** - Policies, procedures, employee responsibilities
2. **Technical Controls** - Firewalls, IDS/IPS, encryption, antivirus, backups
3. **Physical/Operational Controls** - Locks, CCTV, fire prevention systems

Each control is assessed as:
- ✅ **YES** - Control is currently implemented
- ❌ **NO** - Control is NOT implemented (requires attention)

## 📂 Repository Structure


## ⚠️ Key Findings

### Critical Issues Identified:
- All employees have access to sensitive customer data (PII/SPII)
- No encryption for credit card information
- Missing access controls (Least Privilege, Separation of Duties)
- No disaster recovery plans or data backups
- No Intrusion Detection System (IDS) in place
- Weak password policies not enforced

### Compliance Gaps:
- **PCI DSS:** Encryption and access controls needed
- **GDPR:** Data classification and breach notification procedures required
- **SOC:** User access policies need establishment

### Positive Aspects:
- Firewall properly configured
- Antivirus software installed and monitored
- Physical security adequate (locks, CCTV, fire systems)
- GDPR breach notification plan exists

## 🛠️ Frameworks & Standards Referenced
- **NIST Cybersecurity Framework (CSF)**
- **PCI DSS** (Payment Card Industry Data Security Standard)
- **GDPR** (General Data Protection Regulation)
- **SOC** (System and Organizations Controls - Type 1 & 2)

## 📚 Course Information
- **Course:** Google Cybersecurity Professional Certificate
- **Platform:** Coursera
- **Project Type:** Internal Security Audit (Controls and Compliance Assessment)

---

*This is a fictional scenario created for educational purposes as part of the Google Cybersecurity Certificate program.*
