# Log Analysis – TryHackMe Project

## 📘 Overview

This project was completed using the **Intro to Log Analysis** room on [TryHackMe](https://tryhackme.com/).  
I investigated simulated Windows security logs to detect signs of suspicious activity — a foundational task in real SOC environments.

---

## 🧠 Key Skills Practiced

- 🔍 Log Analysis & Threat Detection  
- 🛡️ Event Log Correlation  
- ⚙️ Incident Investigation  
- 🧰 SOC Analyst Workflow Thinking

---

## 🕵️‍♂️ Threat Investigation Highlights

| Task | Focus | Key Finding |
|------|-------|-------------|
| 1 | Host Identification | `WIN-SERVER-01` |
| 2 | Suspicious IP | `203.0.113.4` (multiple failed logins) |
| 3 | Timeline Log Clue | Found keywords: `Supertimeline`, `filehashes` |
| 4 | Log Path Analysis | Detected Path Traversal: `/var/log/nginx/access.log` |
| 5 | Detection Method | Alert Form: `Automated`, `Manual` |

**Pattern:** Detected **7 failed login attempts within 2 minutes** from a single external IP — indicating a brute-force attempt.

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/6ee83377-2f4d-45fe-a55a-569d8f8bd492)
![image](https://github.com/user-attachments/assets/e091dbc4-7621-4d87-ad74-765bcc4fde2d)
![image](https://github.com/user-attachments/assets/2e5e68f9-e4d3-420f-a610-b8583832a037)

---

## ✅ Lessons Learned

This hands-on lab gave me real-world experience in:
- Navigating and interpreting log data
- Detecting anomalies in authentication patterns
- Practicing the mindset of a SOC Tier 1 Analyst

---

