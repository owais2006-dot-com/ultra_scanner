# ultra_scanner
# Ultra Scan

**Ultra Scan** is a powerful, Nmap-based network scanner featuring a sleek, interactive command-line menu. Written entirely in Bash, this tool offers over **25 advanced scanning options**—from basic ping sweeps to deep vulnerability assessments and firewall evasion techniques.

---

## 🚀 Features

- **Interactive CLI UI** with animated headers for an engaging user experience  
- Automatic dependency checks and installs for required tools (`nmap`, `figlet`)  
- Over 25 scan types including:  
  - Ping scan, TCP SYN, UDP scans  
  - OS and Version detection  
  - Aggressive scanning and top/all ports scanning  
  - Firewall evasion techniques  
  - Vulnerability scanning using Nmap scripts  
  - DNS brute forcing, HTTP/FTP/SMB enumeration  
  - Whois lookup, WAF detection, MAC spoofing  
- Export scan results to files for later analysis  
- Safe script execution with user prompt confirmations  
- Designed especially for **security researchers** and **bug bounty hunters**

---

## 📦 Requirements

- `nmap`  
- `figlet`  
- Linux-based OS (Tested on Kali Linux and Ubuntu)

---

## 🔧 Installation & Usage

```bash
git clone https://github.com/ZEEL-007/ultra_scan.git
cd ultra_scan
chmod +x ultra_scan.sh
./ultra_scan.sh
