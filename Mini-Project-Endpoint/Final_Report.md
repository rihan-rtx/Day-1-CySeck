# 🛡️ Enterprise Endpoint Security Risk Assessment

## Overview
This project performs a baseline security risk assessment on an endpoint device.
The assessment includes identifying assets, analyzing threats and vulnerabilities,
researching real-world CVEs, and implementing security hardening measures aligned
with the CIA Triad.

---

## Objectives
- Identify endpoint assets
- Analyze threats, vulnerabilities, and risks
- Research real CVEs from NVD
- Apply baseline security hardening
- Map security controls to CIA Triad

---

## Scope
- Laptop / Desktop
- Operating System
- Web Browser
- Email
- Cloud Storage
- Network

---

## Module 1: Asset Inventory

| Asset | Description | Importance |
|------|------------|------------|
| Laptop | Personal endpoint device | High |
| Operating System | Windows / Linux | High |
| Web Browser | Google Chrome | High |
| Email | Personal Gmail account | High |
| Cloud Storage | Google Drive | Medium |
| Network | Home Wi-Fi connection | Medium |

---

## Module 2: Threat & Risk Analysis

| Asset | Threat | Vulnerability | Risk |
|------|-------|--------------|-----|
| Laptop | Malware | Outdated or no antivirus | Data loss or system damage |
| Operating System | Unauthorized access | Weak password | System compromise |
| Web Browser | Phishing attack | Clicking unknown links | Credential theft |
| Email | Account takeover | No MFA enabled | Data breach |
| Cloud Storage | Data exposure | Misconfigured sharing | Data leakage |
| Network | Unauthorized access | Weak Wi-Fi password | Network misuse |

---

## Module 3: CVE Research

### CVE-2021-44228 (Log4Shell)
- Affected Software: Apache Log4j
- Severity: Critical
- CVSS Score: 10.0
- Impact: Remote Code Execution
- Mitigation: Upgrade Log4j to the latest patched version

### CVE-2023-4863
- Affected Software: Google Chrome
- Severity: High
- Impact: Heap buffer overflow leading to code execution
- Mitigation: Update Chrome to latest version

### CVE-2022-30190
- Affected Software: Microsoft Windows
- Severity: High
- Impact: Remote code execution via MSDT
- Mitigation: Apply Windows security updates

### CVE-2023-23397
- Affected Software: Microsoft Outlook
- Severity: Critical
- Impact: Credential theft without user interaction
- Mitigation: Apply Outlook security patch

### CVE-2022-22965
- Affected Software: Spring Framework
- Severity: Critical
- Impact: Remote code execution
- Mitigation: Upgrade affected framework versions

---

## Module 4: CIA Mapping

| Asset | Confidentiality | Integrity | Availability |
|------|----------------|----------|-------------|
| Operating System | ✔ | ✔ | ✔ |
| Web Browser | ✔ | ✔ | ✔ |
| Email | ✔ | ✔ | ✔ |
| Cloud Storage | ✔ | ✔ | ✔ |
| Network | ✔ | ❌ | ✔ |

---

## Module 5: Hardening Actions

| Hardening Action | Purpose |
|----------------|--------|
| Enable Firewall | Blocks unauthorized network access |
| Install Antivirus | Prevents malware infections |
| Enable Auto Updates | Fixes known vulnerabilities |
| Use Strong Passwords | Prevents brute-force attacks |
| Enable Screen Lock | Prevents unauthorized physical access |

---

## Conclusion
This project demonstrated how endpoint security risks can be identified and
mitigated using fundamental cybersecurity principles. By conducting asset
inventory, threat and risk analysis, CVE research, and applying baseline
hardening controls, the endpoint security posture was significantly improved
in alignment with the CIA Triad.

---

## Resume Statement
Performed endpoint security risk assessment, CVE research, and implemented
baseline hardening controls aligned with CIA Triad.
