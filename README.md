# Task 1 – Port Scanning with Nmap

This repository contains my work for Task 1 of a cybersecurity internship.  
The objective was to scan a local network for open ports using Nmap and identify potential vulnerabilities.

 Tools Used
- Kali Linux (Attacker)
- Windows 10 VM (Target)
- Nmap (Port scanning)
- Wireshark (Optional packet analysis)

 Summary
- Used a **bridged network** in VirtualBox
- Scanned target IP: 192.168.1.8
- Found open ports including: 21, 22, 23, 135, 445, 3389, 8080, 9200, etc.
- Mapped key services to real-world CVEs

Files
- task_1_report.html – Full report with results and analysis
- scan_results.txt – Nmap scan output
- README.md – This file

 Outcome
Gained hands-on experience in network scanning, port enumeration, and vulnerability identification.

SCREENSHOTS FOR REFERENCE:

KALI_IP_PNG:

<img width="958" height="1029" alt="Screenshot 2025-08-04 123021" src="https://github.com/user-attachments/assets/146f3a87-0eb0-40b3-b5ba-309377624a61" />


WINDOWS_IP_PNG:

<img width="960" height="1030" alt="Screenshot 2025-08-04 122946" src="https://github.com/user-attachments/assets/19b6e41e-3518-4b78-8aa7-77846d7d6f4f" />


Ping Test from Kali to Windows Confirmed connectivity between the attacker and target machines:

<img width="959" height="1030" alt="Screenshot 2025-08-04 125821" src="https://github.com/user-attachments/assets/99949401-9aaf-4aac-8c88-6015aa394766" />

NMAP_SCAN_RESULT_PNG:

<img width="907" height="1012" alt="Screenshot 2025-08-04 124339" src="https://github.com/user-attachments/assets/40b811e5-7959-4fa0-957d-29bf590f1740" />



