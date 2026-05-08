# Ethical Hacking Workshop

## Overview

This repository contains the materials, practical exercises, commands, and learning resources used during an Ethical Hacking workshop conducted for students and beginners in cybersecurity.

The workshop focused on introducing fundamental cybersecurity concepts, ethical hacking methodologies, reconnaissance techniques, packet analysis, and security awareness through hands-on demonstrations in a controlled lab environment.

The objective of this workshop was to help participants understand how attackers operate, how security professionals identify vulnerabilities, and how defensive security practices are implemented responsibly.

---

# Topics Covered

* Introduction to Ethical Hacking
* CIA Triad (Confidentiality, Integrity, Availability)
* Types of Hackers
* Web Technologies Overview
* Cybersecurity Career Paths
* Network Reconnaissance
* Nmap Scanning Techniques
* Wireshark Packet Analysis
* Tor Browser Awareness
* TryHackMe Workflow
* Hack The Box Workflow
* Ethical Rules and Responsible Security Practices

---

# Tools Used

| Tool         | Purpose                                |
| ------------ | -------------------------------------- |
| Nmap         | Network scanning and host discovery    |
| Wireshark    | Packet capture and traffic analysis    |
| Tor Browser  | Privacy and anonymity awareness        |
| TryHackMe    | Hands-on cybersecurity labs            |
| Hack The Box | Practical penetration testing labs     |
| Windows CMD  | Networking and reconnaissance commands |

---

# Practical Commands Demonstrated

## Networking Commands

```bash
ipconfig
arp -a
netsh wlan show profiles
netsh wlan show interfaces
```

## Nmap Commands

### Host Discovery

```bash
nmap -sn 192.168.1.0/24
```

### Basic Scan

```bash
nmap 192.168.1.10
```

### Service Version Detection

```bash
nmap -sV 192.168.1.10
```

### OS Detection

```bash
nmap -O 192.168.1.10
```

### Aggressive Scan

```bash
nmap -A 192.168.1.10
```

### Common CTF Scan

```bash
nmap -sC -sV 192.168.1.10
```

### Save Scan Output

```bash
nmap -A 192.168.1.10 -oN scan.txt
```

---

# Wireshark Filters

| Purpose       | Filter                    |
| ------------- | ------------------------- |
| HTTP Traffic  | `http`                    |
| HTTPS Traffic | `tls`                     |
| DNS Queries   | `dns`                     |
| ICMP Packets  | `icmp`                    |
| TCP Traffic   | `tcp`                     |
| UDP Traffic   | `udp`                     |
| Specific IP   | `ip.addr == 192.168.1.10` |
| Specific Port | `tcp.port == 80`          |

---

# Learning Outcomes

Participants learned:

* Basic ethical hacking methodology
* Network scanning and enumeration
* Packet inspection and protocol analysis
* Security awareness concepts
* Safe use of cybersecurity tools
* Practical cybersecurity lab workflow
* Responsible and legal security testing practices

---

# Repository Structure

```text
ethical-hacking-workshop/
│
├── README.md
├── presentations/
├── practicals/
├── commands/
├── screenshots/
├── notes/
└── resources/
```

---

# Workshop Presentation

The repository includes the workshop presentation covering:

* Ethical Hacking fundamentals
* CIA Triad
* Types of Hackers
* Cybersecurity careers
* Security tools overview
* Defensive security concepts

---

# Platforms Practiced

## TryHackMe

Used for:

* Beginner cybersecurity labs
* Enumeration practice
* Network security learning
* Hands-on penetration testing exercises

## Hack The Box

Used for:

* Practical cybersecurity environments
* Vulnerability assessment practice
* Security testing workflow understanding

---

# Ethical Guidelines

This workshop was conducted strictly for educational and defensive cybersecurity purposes.

Rules followed during the workshop:

* Never scan networks without authorization
* Perform activities only in lab environments
* Use tools responsibly and ethically
* Respect privacy and legal boundaries
* Focus on defence through offence methodology

---

# Skills Demonstrated

* Network Reconnaissance
* Packet Analysis
* Enumeration
* Security Awareness
* Basic Penetration Testing
* Documentation
* Cybersecurity Lab Workflow
* Ethical Security Practices

---

# Career Relevance

This workshop helps build foundational skills relevant for:

* SOC Analyst
* Security Analyst
* Penetration Tester
* Incident Response
* Cybersecurity Internships

---

# Author

**Pooja N**
MCA Student | Cybersecurity Enthusiast | SOC Analyst Aspirant

---

# Disclaimer

This repository is created strictly for educational purposes.

All demonstrations, commands, and tools shown in this repository were used in controlled lab environments with proper authorization. Unauthorized access to systems or networks is illegal and unethical.

---

# Acknowledgement

Special thanks to the faculty members, organizers, and participants who contributed to the successful completion of this workshop and encouraged practical cybersecurity learning.
