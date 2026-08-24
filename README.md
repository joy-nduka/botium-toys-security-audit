# Botium Toys Security Audit

As part of the Google Cybersecurity Certificate program, I conducted an internal security audit for Botium Toys (a fictional company), covering asset assessment, risk scoring, and a controls/compliance gap analysis.

## Project Overview

- **Goal:** Assess Botium Toys' existing assets, controls, and compliance practices to determine what improvements were needed to strengthen their overall security posture.
- **Scope:** The company's full security program, including employee equipment, internal network, systems (accounting, ecommerce, database, inventory), and data storage.
- **Framework used:** NIST Cybersecurity Framework (CSF), starting with the *Identify* function to catalog and classify assets.
- **Risk score:** 8/10, driven mainly by weak access controls and incomplete compliance with data protection standards.

## Part 1: Scope, Goals & Risk Assessment

Botium Toys had inadequate management of its assets and lacked several controls required for compliance with U.S. and international regulations.

**Key findings:**
- All employees had access to internal data, including cardholder data and customer PII/SPII, with no separation of duties or least privilege in place.
- Customer credit card data was stored and transmitted without encryption.
- No intrusion detection system (IDS) was in place, and there were no disaster recovery plans or data backups.
- The password policy was outdated and not centrally enforced, creating both security and productivity issues.
- On the positive side, the company had a working firewall, active antivirus monitoring, and solid physical security (locks, CCTV, fire detection systems).

📄 [Full report: Scope, Goals & Risk Assessment](./reports/scope-goals-risk-assessment.pdf)

## Part 2: Controls & Compliance Assessment

### Controls Assessment Checklist

| Control | In Place? |
|---|---|
| Least Privilege | No |
| Disaster recovery plans | No |
| Password policies | Yes (exists, but weak/outdated) |
| Separation of duties | No |
| Firewall | Yes |
| Intrusion detection system (IDS) | No |
| Backups | No |
| Antivirus software | Yes |
| Manual monitoring/maintenance for legacy systems | Yes (no regular schedule) |
| Encryption | No |
| Password management system | No |
| Locks (offices, storefront, warehouse) | Yes |
| CCTV surveillance | Yes |
| Fire detection/prevention | Yes |

### Compliance Checklist

**PCI DSS**

| Best Practice | Adhered To? |
|---|---|
| Only authorized users access cardholder data | No |
| Credit card data securely stored/transmitted internally | No |
| Data encryption procedures implemented | No |
| Secure password management policies adopted | No |

**GDPR**

| Best Practice | Adhered To? |
|---|---|
| EU customer data kept private/secured | No |
| 72-hour breach notification plan in place | Yes |
| Data properly classified and inventoried | No |
| Privacy policies/procedures enforced | Yes |

**SOC (Type 1 & 2)**

| Best Practice | Adhered To? |
|---|---|
| User access policies established | No |
| Sensitive data (PII/SPII) kept confidential | No |
| Data integrity maintained | Yes |
| Data availability to authorized users | Yes |

📄 [Full checklist: Controls & Compliance Assessment](./reports/controls-compliance-checklist.pdf)

## Recommendations

To protect the confidentiality of data, Botium Toys should implement: least privilege, disaster recovery plans, stronger password policies, separation of duties, an IDS, regular backups, encryption, and a centralized password management system.

Priority compliance gaps to close: least privilege, encryption, and separation of duties — these affect PCI DSS, GDPR, and SOC compliance simultaneously, so fixing them gives the most risk reduction for the effort.

## Skills Demonstrated

- Risk assessment and scoring
- NIST Cybersecurity Framework (CSF) application
- Compliance analysis (PCI DSS, GDPR, SOC)
- Controls evaluation and gap analysis
- Technical writing and documentation

---# Botium Toys Security Audit

As part of the Google Cybersecurity Certificate program, I conducted a full security audit for Botium Toys (a fictional company), covering asset assessment, risk scoring, and a controls/compliance gap analysis.

## Project Overview

- **Objective:** Assess Botium Toys' existing assets, controls, and compliance practices to determine what improvements were needed to strengthen their overall security posture.
- **Scope:** The company's full security program, including employee equipment, internal network, systems (accounting, ecommerce, database, inventory), and data storage.
- **Framework used:** NIST Cybersecurity Framework (CSF), starting with the *Identify* function to catalog and classify assets.
- **Risk score:** 8/10, driven mainly by weak access controls and incomplete compliance with data protection standards.

## Part 1: Scope, Goals & Risk Assessment

Botium Toys had inadequate management of its assets and lacked several controls required for compliance with U.S. and international regulations.

**Key findings:**
- All employees had access to internal data, including cardholder data and customer PII/SPII, with no separation of duties or least privilege in place.
- Customer credit card data was stored and transmitted without encryption.
- No intrusion detection system (IDS) was in place, and there were no disaster recovery plans or data backups.
- The password policy was outdated and not centrally enforced, creating both security and productivity issues.
- On the positive side, the company had a working firewall, active antivirus monitoring, and solid physical security (locks, CCTV, fire detection systems).

📄 [Full report: Scope, Goals & Risk Assessment](./reports/scope-goals-risk-assessment.pdf)

## Part 2: Controls & Compliance Assessment

### Controls Assessment Checklist

| Control | In Place? |
|---|---|
| Least Privilege | No |
| Disaster recovery plans | No |
| Password policies | Yes (exists, but weak/outdated) |
| Separation of duties | No |
| Firewall | Yes |
| Intrusion detection system (IDS) | No |
| Backups | No |
| Antivirus software | Yes |
| Manual monitoring/maintenance for legacy systems | Yes (no regular schedule) |
| Encryption | No |
| Password management system | No |
| Locks (offices, storefront, warehouse) | Yes |
| CCTV surveillance | Yes |
| Fire detection/prevention | Yes |

### Compliance Checklist

**PCI DSS**

| Best Practice | Adhered To? |
|---|---|
| Only authorized users access cardholder data | No |
| Credit card data securely stored/transmitted internally | No |
| Data encryption procedures implemented | No |
| Secure password management policies adopted | No |

**GDPR**

| Best Practice | Adhered To? |
|---|---|
| EU customer data kept private/secured | No |
| 72-hour breach notification plan in place | Yes |
| Data properly classified and inventoried | No |
| Privacy policies/procedures enforced | Yes |

**SOC (Type 1 & 2)**

| Best Practice | Adhered To? |
|---|---|
| User access policies established | No |
| Sensitive data (PII/SPII) kept confidential | No |
| Data integrity maintained | Yes |
| Data availability to authorized users | Yes |

📄 [Full checklist: Controls & Compliance Assessment](./reports/controls-compliance-checklist.pdf)

## Recommendations

To protect the confidentiality of data, Botium Toys should implement: least privilege, disaster recovery plans, stronger password policies, separation of duties, an IDS, regular backups, encryption, and a centralized password management system.

Priority compliance gaps to close: least privilege, encryption, and separation of duties — these affect PCI DSS, GDPR, and SOC compliance simultaneously, so fixing them gives the most risk reduction for the effort.

---
*This audit was conducted using a fictional company scenario provided by the Google Cybersecurity Certificate program. Any data shown is simulated.*

*This audit was conducted using a fictional company scenario provided by the Google Cybersecurity Certificate program. Any data shown is simulated.*
