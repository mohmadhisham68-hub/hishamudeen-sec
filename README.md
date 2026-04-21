# 🔐 Cybersecurity Portfolio — Mohamed Hishamudeen

> Cybersecurity diploma student | Digital Forensics | Penetration Testing | Security Automation  
> 📍 Singapore &nbsp;|&nbsp; mohmadhisham68@gmail.com &nbsp;|&nbsp; +65 8211 8980

---

## About Me

I'm a cybersecurity graduate from PSB Academy Singapore, specialising in digital forensics and countermeasures. This repository contains hands-on security tools I built to demonstrate practical skills in offensive reconnaissance, defensive monitoring, and security automation.

All tools are built for **educational use and authorized testing only**.

---

## Projects

| # | Project | Category | Key Skills |
|---|---|---|---|
| 1 | [🔍 Network Port Scanner](./1-network-scanner/) | Offensive / Recon | Sockets, threading, service fingerprinting |
| 2 | [🔐 Password Security Auditor](./2-password-auditor/) | Defensive / Risk | Entropy, cryptography, pattern detection |
| 3 | [🛡️ Security Log Analyser](./3-log-analyzer/) | Blue Team / SOC | Log parsing, IDS logic, MITRE ATT&CK |

---

## 1. Network Port Scanner

Multi-threaded Python port scanner for authorized network reconnaissance. Identifies open TCP ports, maps services, grabs banners, flags risky exposures.

```bash
python3 scanner.py --target 192.168.1.1 --ports 1-1024 --banner
```

**Skills:** Python sockets · Threading · Network fundamentals · Service enumeration

[→ View Project](./1-network-scanner/)

---

## 2. Password Security Auditor

Analyses passwords using real attacker methodology — entropy calculation, crack time estimation, keyboard walk detection, common password checking, and SHA-1 k-anonymity for HaveIBeenPwned.

```bash
python3 password_auditor.py
```

**Skills:** Cryptography · Entropy · Regex · Defensive security · Risk assessment

[→ View Project](./2-password-auditor/) https://github.com/mohmadhisham68-hub/password-security-auditor

---

## 3. Security Log Analyser & Intrusion Detector

Blue team tool that parses Linux auth logs to detect brute force attacks, password spray, off-hours logins, root access, privilege escalation, and threat intel matches. Maps every finding to MITRE ATT&CK.

```bash
python3 log_analyser.py --demo
```

**Skills:** Log analysis · IDS logic · MITRE ATT&CK · Incident response · SOC methodology

[→ View Project](./3-log-analyzer/)

---

## Technical Skills

```
Security Tools    Kali Linux · Wireshark · Nmap · Metasploit · Autopsy · OpenVAS · Splunk
Programming       Python · Bash · PowerShell
Frameworks        MITRE ATT&CK · OWASP Top 10 · NIST CSF
Platforms         TryHackMe · HackTheBox · VirtualBox
```

---

## Certifications

| Certification | Status |
|---|---|
| Google Cybersecurity Professional Certificate | ✅ Earned (Oct 2025) |
| CompTIA Security+ (SY0-701) | 🔄 In Progress |
| ISC² Certified in Cybersecurity (CC) | 🔄 In Progress |
| Splunk Fundamentals 1 | 📋 Planned |

---

## Let's Connect

- 📧 mohmadhisham68@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/hishamudeen)
- 🌐 Singapore — open to cybersecurity internships and entry-level roles

---

> ⚠️ **Legal Notice:** All tools in this repository are for educational purposes and authorized testing only. Never use these tools against systems you don't own or have explicit permission to test.
