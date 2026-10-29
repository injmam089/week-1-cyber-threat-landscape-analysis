# Week 1 — Cyber Threat Landscape Analysis & Strategic Planning

![Cybersecurity](https://img.shields.io/badge/Focus-Cybersecurity-blue)
![Internship](https://img.shields.io/badge/Internship-Cyber%20Security%20Analyst-orange)
![Week](https://img.shields.io/badge/Week-1-green)
![Year](https://img.shields.io/badge/Year-2026-lightgrey)

## 📌 Overview

This repository contains my **Week 1 Cyber Security Analyst internship task** focused on **Cyber Threat Landscape Analysis and Strategic Cybersecurity Planning**.

The objective of this task was to research the current cyber threat environment, identify major threats and vulnerabilities, assess associated risks, and develop a practical strategic plan for prevention, detection, response, mitigation, and recovery.

## 🎯 Objectives

- Analyze the current cyber threat landscape.
- Research major and emerging cyber threats.
- Assess threat likelihood and business impact.
- Identify common organizational vulnerabilities.
- Recommend preventive and mitigation controls.
- Develop a phased cybersecurity strategy.
- Define measurable security KPIs.
- Document an incident-response framework.
- Present findings using professional charts and structured analysis.

## 🛡️ Major Threats Analyzed

| Threat | Likelihood | Impact | Risk Score | Priority |
|---|---:|---:|---:|---|
| Ransomware / Double Extortion | 5/5 | 5/5 | 20 | Critical |
| Phishing / Social Engineering | 5/5 | 4/5 | 20 | Critical |
| Infostealers / Credential Theft | 4/5 | 4/5 | 16 | High |
| Supply Chain / Third-Party Compromise | 3/5 | 5/5 | 15 | High |
| DDoS / Service Disruption | 4/5 | 3/5 | 12 | High |

> Risk score = Likelihood × Impact. The scores in this table are an educational analyst assessment and should be recalibrated for a specific organization.

## 🔍 Key Areas Covered

### 1. Ransomware
Analysis of ransomware, double-extortion, common entry paths, organizational weaknesses, business impact, and recommended controls such as MFA, segmentation, immutable backups, EDR, patch management, and recovery testing.

### 2. Phishing & Social Engineering
Analysis of credential theft, malicious links, impersonation, business email compromise, and human-factor risks, with recommendations including phishing-resistant MFA, email security, DMARC/SPF/DKIM, awareness training, and verification procedures.

### 3. Infostealers & Credential Theft
Analysis of malware that steals browser credentials, cookies, session tokens and other secrets, with defensive measures including EDR, browser hardening, password managers, unique credentials, session revocation, and secure software practices.

### 4. Distributed Denial-of-Service (DDoS)
Analysis of attacks against network and application availability, with controls including upstream DDoS protection, rate limiting, traffic monitoring, redundancy, and tested response procedures.

### 5. Supply-Chain & Third-Party Compromise
Analysis of risks arising from vendors, SaaS providers, open-source dependencies and CI/CD pipelines, with controls including SBOMs, dependency verification, least-privilege vendor access, secure CI/CD, and vendor risk management.

## 📊 Risk Assessment Methodology

A qualitative **5×5 risk matrix** was used:

**Risk Score = Likelihood × Impact**

| Score | Classification |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–15 | High |
| 16–25 | Critical |

## 🗺️ Strategic Cybersecurity Roadmap

### Phase 1 — Immediate Actions (0–30 Days)
- Inventory internet-facing assets and privileged accounts.
- Enforce MFA on critical accounts.
- Patch critical exposed vulnerabilities.
- Validate backup isolation and restoration.
- Improve endpoint protection and logging.
- Establish incident-response contacts and escalation paths.

### Phase 2 — Stabilization (31–90 Days)
- Implement network segmentation.
- Establish formal vulnerability-management SLAs.
- Strengthen email security.
- Establish vendor-risk assessments.
- Conduct security-awareness training.
- Define baseline security metrics.

### Phase 3 — Maturity (3–6 Months)
- Improve SIEM and detection engineering.
- Integrate threat intelligence.
- Maintain an SBOM for critical applications.
- Harden CI/CD and secrets management.
- Conduct tabletop incident-response exercises.
- Test disaster recovery.

### Phase 4 — Continuous Improvement (6–12 Months)
- Continuously monitor security controls.
- Conduct authorized security testing.
- Review privileged and vendor access.
- Update threat models for new technologies.
- Use incidents and near misses to improve controls.

## 📈 Security KPIs

The report proposes tracking:

- Critical vulnerability remediation time
- MFA coverage
- Backup restoration success
- Mean Time to Detect (MTTD)
- Mean Time to Respond (MTTR)
- Security-awareness training completion
- Critical vendor assessment coverage
- DDoS response readiness

## 📁 Repository Structure

```text
week-1-cyber-threat-landscape-analysis/
│
├── README.md
│
├── report/
│   └── Week_1_Cyber_Threat_Landscape_Analysis_2026.docx
│
├── charts/
│   ├── threat-risk-matrix.png
│   └── threat-comparison.png
│
└── references/
    └── sources.md
```

## 📚 References

The analysis uses recent publicly available cybersecurity intelligence and industry research, including ENISA, Verizon, Microsoft, Cloudflare, IBM, and Palo Alto Networks Unit 42.

See [`references/sources.md`](references/sources.md) for the source list.

## ⚠️ Ethical & Legal Scope

This project is intended for **educational and defensive cybersecurity analysis**.

No unauthorized scanning, exploitation, credential theft, persistence, malware deployment, or access to systems without permission is performed or encouraged as part of this project.

## 👨‍💻 Author

**Injmam Ansari**

Cybersecurity Intern | BCA Student

---

⭐ This repository documents my Week 1 cybersecurity internship work and demonstrates skills in threat research, risk assessment, strategic planning, security controls, and incident-response planning.
