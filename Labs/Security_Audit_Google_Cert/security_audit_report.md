# 🛡️ Internal Security Audit – Botium Toys (Fictional Company)

## 🎯 Objective

Conduct an internal IT audit at **Botium Toys**, a fictional U.S.-based toy company, to identify and evaluate security risks, compliance issues, and potential vulnerabilities. The audit follows the **NIST Cybersecurity Framework (CSF)** and includes controls, risk assessments, and regulatory compliance checks.

---

## 🏢 Company Profile

- **Name**: Botium Toys  
- **Location**: Single physical U.S. location (office, storefront, warehouse)  
- **Business**: Designs and sells toys both in-store and online  
- **IT Scope**: Supports local infrastructure and growing international e-commerce presence  
- **Concern**: Increased risk exposure due to growth, lack of formal planning, and regulatory requirements (e.g. online payments, GDPR compliance for EU customers)

---

## 🔍 Audit Scope & Goals

- **Scope**: All IT systems handling sensitive data (e.g. customer info, payments), internet-facing services, and regulatory compliance areas.
- **Goals**:
  - Identify potential security threats and vulnerabilities
  - Assess controls in place using the NIST CSF
  - Verify compliance with relevant data protection regulations (PCI DSS, GDPR)
  - Recommend mitigations for high-risk items

---

## 🧾 Assets Reviewed

| Category         | Example Assets                             |
|------------------|--------------------------------------------|
| Network Devices  | Routers, firewalls, wireless APs           |
| Servers          | Web server, internal application servers   |
| Endpoints        | Staff laptops, point-of-sale (POS) systems |
| Software         | E-commerce platform, CMS, accounting apps  |
| Data             | Customer PII, payment data, product data   |

---


## ✅ Controls Assessment Checklist

| Control                                                                 | In Place |
|-------------------------------------------------------------------------|----------|
| Least Privilege                                                         | ❌ No    |
| Disaster Recovery Plans                                                 | ❌ No    |
| Password Policies                                                       | ❌ No 
| Separation of Duties                                                    | ❌ No    |
| Firewall                                                                | ✅ Yes   |
| Intrusion Detection System (IDS)                                        | ❌ No    |
| Backups                                                                 | ❌ No    |
| Antivirus Software                                                      | ✅ Yes   |
| Manual Monitoring & Maintenance of Legacy Systems                       | ❌ No  |
| Encryption                                                              | ❌ No    |
| Password Management System                                              | ❌ No    |
| Locks (offices, storefront, warehouse)                                  | ✅ Yes   |
| Closed-Circuit Television (CCTV) Surveillance                           | ✅ Yes   |
| Fire Detection/Prevention (alarm, sprinkler system, etc.)               | ✅ Yes   |

---

## 🛡️ Compliance Checklist

### **Payment Card Industry Data Security Standard (PCI DSS)**

| Best Practice                                                                                   | In Place |
|--------------------------------------------------------------------------------------------------|----------|
| Only authorized users have access to customers’ credit card information                         | ❌ No    |
| Credit card info is stored, accepted, processed, and transmitted securely                       | ❌ No    |
| Data encryption procedures are in place for credit card data                                    | ❌ No    |
| Secure password management policies are adopted                                                 | ❌ No    |

---

### **General Data Protection Regulation (GDPR)**

| Best Practice                                                                                   | In Place |
|--------------------------------------------------------------------------------------------------|----------|
| E.U. customers’ data is kept private/secured                                                     | ❌ No  |
| Plan in place to notify E.U. customers within 72 hours if data is compromised                   | ✅ Yes   |
| Data is properly classified and inventoried                                                     | ✅ Yes   |
| Privacy policies, procedures, and documentation are enforced                                     | ✅ Yes   |

---

### **System and Organization Controls (SOC Type 1 & 2)**

| Best Practice                                                                                   | In Place |
|--------------------------------------------------------------------------------------------------|----------|
| User access policies are established                                                             | ❌ No    |
| Sensitive data (PII/SPII) is kept confidential                                                   | ❌ No    |
| Data integrity is ensured (consistent, complete, accurate, validated)                            | ✅ Yes   |
| Data is available to authorized individuals                                                      | ✅ Yes   |

---

## 📝 Recommendations to IT Manager

1. **Implement Access Controls & Least Privilege**
   - Restrict access to sensitive data (e.g., PII, cardholder info) based on job role.
   - Apply separation of duties to reduce internal risk.

2. **Deploy Encryption**
   - Encrypt all stored and transmitted credit card and customer data to comply with PCI DSS and GDPR.

3. **Create a Disaster Recovery & Backup Strategy**
   - Define and test a disaster recovery plan with scheduled automated backups of critical systems.

4. **Upgrade Password Policies & Management**
   - Enforce strong password complexity.
   - Deploy a centralized password management system.

5. **Install IDS/IPS Systems**
   - Deploy an intrusion detection/prevention system to monitor for malicious activity.

6. **Regularly Maintain and Monitor Legacy Systems**
7. **Begin SOC Readiness and PCI/GDPR Compliance Initiatives**
  

---


## 🧠 Key Findings

- No formal access control or user account management policies
- No MFA, leaving admin accounts vulnerable to brute force attacks
- Backups exist but are neither encrypted nor regularly tested
- Company may be non-compliant with GDPR and PCI DSS regulations


