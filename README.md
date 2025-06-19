# 🧠 SIEM Detection Engineering with Wazuh + Sysmon

## 🎯 Objective
Detect and respond to host-based and network-based intrusions using Wazuh, Sysmon, and Sigma rules.

## 🧰 Stack Used
- Wazuh Manager + Agents
- Windows + Linux Hosts
- Sysmon
- Sigma Rule Framework
- ELK Stack (Optional: Kibana)

## 🧪 Use Cases Implemented
- PowerShell Obfuscation Detection
- Suspicious Command Line (base64, enc)
- Process Injection / Rundll32
- Registry Persistence Attempts
- New Service Creation

## 📂 Folder Structure
- /screenshots     # Alert evidence
- /sigma-rules     # Custom detection logic
- /reports         # Detection mapping and incident writeups

## ⚙️ Configuration Files
- `ossec.conf` (Wazuh)
- `sysmon.xml`
- `.yml` Sigma rule files

## 📝 License
MIT
