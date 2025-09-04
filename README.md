# 💽 Parking Lot USB Exercise – Attack Vector Analysis

## 📌 Overview
This project investigates the security risks of discovering and analyzing an unknown USB drive in a hospital setting.  
The exercise demonstrates how USB baiting attacks work, evaluates both attacker and target perspectives, and proposes security measures to reduce organizational risk.

---

## 🕵️ Scenario
While arriving at **Rhetorical Hospital**, a USB stick with the hospital logo was discovered in the parking lot.  
The device was analyzed in a **safe virtualized environment** to prevent unintended damage to production systems.  

The USB contained a mix of personal and professional files belonging to an HR manager, Jorge Bailey, including employee shift schedules and personal photos.

---

## 📂 Contents Analysis
- The device contained **Personally Identifiable Information (PII)** such as employee-related data.  
- Work-related files like schedules and letters were stored alongside personal items.  
- Mixing personal and business data increases the risk of **exposure, leakage, and misuse**.

---

## 🎭 Attacker Mindset
- An attacker could impersonate Jorge or launch **phishing/social engineering attacks** on hospital staff.  
- Files might be intentionally staged as bait to trick employees into connecting the device.  
- Attackers could exploit personal contacts, work schedules, or HR documents to infiltrate hospital operations.  

---

## ⚠️ Risk Analysis
- Malicious USBs could carry **malware** such as:
  - 🛑 Keyloggers  
  - 🔐 Ransomware  
  - 🐴 Trojans  
- Risks if plugged into a corporate workstation:
  - Theft of patient data, credentials, or financial information  
  - Disruption of hospital operations via DoS or ransomware  
  - Blackmail, fraud, or identity theft  

### ✅ Recommended Mitigations
- **Technical Controls:** Disable autorun, restrict USB ports, deploy endpoint security.  
- **Operational Controls:** Train employees to avoid plugging in unknown USB drives.  
- **Managerial Controls:** Enforce clear data handling and device usage policies.  

---

## 📑 Deliverables
This repository contains:
- 📝 Completed **Parking Lot USB Exercise** document with detailed analysis (Contents, Attacker Mindset, Risk Analysis).  
- 📄 [Full Report (Google Doc)](https://docs.google.com/document/d/1Axv2mjAc-5pvSSza3bFtYfgllc5o4xEdIqh-pCO1k0U/edit?usp=sharing)  

---

## 🎯 Key Takeaway
This exercise highlights the **human factor risks** in cybersecurity and demonstrates why **USB baiting is a powerful social engineering attack**.  
By combining **technical defenses** with **employee awareness and organizational policies**, companies can significantly reduce the risks associated with malicious devices.
