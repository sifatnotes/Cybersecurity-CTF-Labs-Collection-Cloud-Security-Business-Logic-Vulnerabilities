# Cybersecurity-CTF-Labs-Collection-Cloud-Security-Business-Logic-Vulnerabilities
A curated, searchable index of hands-on cybersecurity labs covering cloud misconfigurations, IAM abuse, container registries, SSRF metadata attacks, and e-commerce business logic flaws from Learn SecByte.
# Cloud Security & Business Logic CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs covering cloud infrastructure misconfigurations, serverless exposure, SSRF metadata exploitation, IAM privilege escalation, and e-commerce business logic vulnerabilities hosted on Learn SecByte.

This repository is designed for cloud security engineers, penetration testers, CTF players, application security analysts, and red/blue team practitioners seeking practical, hands-on security training.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Cloud Infrastructure & Serverless Security](#cloud-infrastructure--serverless-security)
  - [Cloud IAM & Container Registry Security](#cloud-iam--container-registry-security)
  - [Business Logic & E-Commerce Vulnerabilities](#business-logic--e-commerce-vulnerabilities)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Securing modern digital architecture requires a thorough understanding of both underlying cloud infrastructure and high-level application business logic. From exposed cloud metadata endpoints and overshared IAM roles to subtle logic flaws in payment workflows, identifying misconfigurations is essential to preventing real-world security incidents.

This repository organizes hands-on cybersecurity labs from Learn SecByte into logical learning paths covering cloud security and application logic analysis.

---

## Lab Collection & Index

| Lab Title | Primary Category | Domain Focus | Access Link |
| :--- | :--- | :--- | :--- |
| **Container Registry Exposure** | Cloud Security | Registry Misconfigurations | [Access Lab](https://learn.secbyte.org/ctf/container-registry-exposure-from-misconfiguration-to-inciden) |
| **Cloud Function Exposure** | Cloud Security | Serverless Security | [Access Lab](https://learn.secbyte.org/ctf/cloud-function-exposure) |
| **Cloud Metadata Abuse (SSRF)** | Cloud Security | IMDS / Instance Credentials | [Access Lab](https://learn.secbyte.org/ctf/cloud-metadata-abuse-from-ssrf-to-instance-credentials) |
| **Misconfigured IAM Roles** | Cloud Security | Access Control & Overshared Roles | [Access Lab](https://learn.secbyte.org/ctf/misconfigured-iam-overshared-roles) |
| **Public Blob Storage Exposure** | Cloud Security | Cloud Storage Security | [Access Lab](https://learn.secbyte.org/ctf/public-blob-storage-exposure) |
| **Exposed S3 Bucket Assessment** | Cloud Security | AWS Cloud Storage | [Access Lab](https://learn.secbyte.org/ctf/exposed-s3-bucket-public-cloud-storage-assessment) |
| **Workflow Bypass** | Business Logic | Application Flow & Logic | [Access Lab](https://learn.secbyte.org/ctf/workflow-bypass-breaking-and-defending-application-logic) |
| **Inventory Manipulation** | Business Logic | Cart & Count Integrity | [Access Lab](https://learn.secbyte.org/ctf/inventory-manipulation-trusting-the-cart-breaking-the-count) |
| **Negative Balance Attack** | Business Logic | Financial & Numerical Logic | [Access Lab](https://learn.secbyte.org/ctf/negative-balance-attack) |
| **Checkout Bypass** | Business Logic | Payment Gateway Flows | [Access Lab](https://learn.secbyte.org/ctf/checkout-bypass-broken-cart-payment-flows) |
| **Loyalty Point Abuse** | Business Logic | Reward Logic & Fraud Detection | [Access Lab](https://learn.secbyte.org/ctf/loyalty-point-abuse-reward-logic-fraud-detection) |
| **Gift Card Abuse** | Business Logic | Enumeration & Reuse Fraud | [Access Lab](https://learn.secbyte.org/ctf/gift-card-abuse-enumeration-reuse-fraud-detection) |

---

## Categories

### Cloud Infrastructure & Serverless Security
Hands-on CTF labs exploring cloud storage exposures, serverless function security, and instance metadata access vectors:

* **Cloud Metadata Abuse (SSRF):** Exploiting Server-Side Request Forgery (SSRF) vulnerabilities to query Instance Metadata Services (IMDS) and extract temporary IAM credentials.
  * Lab Link: https://learn.secbyte.org/ctf/cloud-metadata-abuse-from-ssrf-to-instance-credentials
* **Exposed S3 Bucket Assessment:** Auditing and exploiting publicly readable/writable AWS S3 buckets and assessing cloud data leakage.
  * Lab Link: https://learn.secbyte.org/ctf/exposed-s3-bucket-public-cloud-storage-assessment
* **Public Blob Storage Exposure:** Identifying unauthenticated access controls across cloud object storage containers.
  * Lab Link: https://learn.secbyte.org/ctf/public-blob-storage-exposure
* **Cloud Function Exposure:** Evaluating security risks in serverless cloud functions, endpoint exposures, and overly permissive function roles.
  * Lab Link: https://learn.secbyte.org/ctf/cloud-function-exposure

### Cloud IAM & Container Registry Security
Practical labs focusing on identity management misconfigurations and exposed private container infrastructure:

* **Misconfigured IAM Overshared Roles:** Identifying overly permissive IAM policies, privilege escalation paths, and broad permissions in cloud environments.
  * Lab Link: https://learn.secbyte.org/ctf/misconfigured-iam-overshared-roles
* **Container Registry Exposure:** Enumerating unauthenticated container registries to extract internal application images and embedded secrets.
  * Lab Link: https://learn.secbyte.org/ctf/container-registry-exposure-from-misconfiguration-to-inciden

### Business Logic & E-Commerce Vulnerabilities
Hands-on security labs focused on breaking complex application logic, workflow state machines, and payment validation controls:

* **Workflow Bypass:** Circumventing required multi-step application processes and access restrictions through parameter manipulation.
  * Lab Link: https://learn.secbyte.org/ctf/workflow-bypass-breaking-and-defending-application-logic
* **Inventory Manipulation:** Abusing client-side cart trusting and parameter manipulation to break item count and price checks.
  * Lab Link: https://learn.secbyte.org/ctf/inventory-manipulation-trusting-the-cart-breaking-the-count
* **Negative Balance Attack:** Exploiting integer handling and validation oversights to force negative totals or balance credits.
  * Lab Link: https://learn.secbyte.org/ctf/negative-balance-attack
* **Checkout Bypass:** Subverting payment gateway status checks, cart verification flows, and transaction authorization routines.
  * Lab Link: https://learn.secbyte.org/ctf/checkout-bypass-broken-cart-payment-flows
* **Loyalty Point Abuse:** Analyzing reward points accumulation, validation logic errors, and fraud detection techniques.
  * Lab Link: https://learn.secbyte.org/ctf/loyalty-point-abuse-reward-logic-fraud-detection
* **Gift Card Abuse:** Exploiting weak gift card generation algorithms, code enumeration, and voucher reuse flaws.
  * Lab Link: https://learn.secbyte.org/ctf/gift-card-abuse-enumeration-reuse-fraud-detection

---

## Learning Path

Follow this structured roadmap to build comprehensive expertise in modern cloud and application security:

1. **Cloud Data & Object Storage Security**
   - Audit public S3 buckets and blob storage containers for sensitive data leaks.
   - Investigate exposed container registries and public cloud functions.
2. **Cloud Metadata & IAM Elevation**
   - Master SSRF techniques to target metadata endpoints and extract temporary cloud credentials.
   - Analyze overshared IAM policies to identify privilege escalation paths.
3. **Application Logic & Workflow Defense**
   - Study multi-step workflow bypasses and state machine manipulation.
4. **E-Commerce & Financial Logic Auditing**
   - Test cart mechanisms for price/quantity tampering and negative balance flaws.
   - Evaluate payment gateway flows, reward point algorithms, and voucher systems.

---

## How to Use the Labs

1. Select a lab from the collection index or categories above.
2. Launch the interactive target environment directly on Learn SecByte.
3. Complete the hands-on goals to perform security analysis, exploitation, and vulnerability verification.
4. Review recommended security baselines and remediation guidance to implement effective defenses.

---

## Disclaimer

This repository is strictly provided for educational, research, and authorized testing purposes. All concepts, methodologies, and practice environments are designed to help cybersecurity professionals, developers, and defenders identify vulnerabilities and harden systems against attack. Performing unauthorized testing against systems or networks without explicit permission is strictly prohibited.
