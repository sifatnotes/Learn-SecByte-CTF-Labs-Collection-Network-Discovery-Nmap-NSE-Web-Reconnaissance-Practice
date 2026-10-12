# Learn-SecByte-CTF-Labs-Collection-Network-Discovery-Nmap-NSE-Web-Reconnaissance-Practice
A curated index of hands-on cybersecurity CTF labs covering ARP/ICMP Host Discovery, Nmap Scripting Engine (NSE), Virtual Host Enumeration, Directory Fuzzing, and HTTP Header Analysis from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository provides a structured, searchable index of hands-on cybersecurity labs designed for security students, CTF players, penetration testers, SOC analysts, and security researchers seeking to build practical mastery in network reconnaissance, service fingerprinting, and web attack surface mapping.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Thorough reconnaissance is the foundation of every successful penetration testing engagement. Hosted on [Learn SecByte](https://learn.secbyte.org/), this collection of CTF challenges focuses on the initial phases of the cyber attack lifecycle.

From low-level ARP/ICMP host discovery and advanced Nmap Scripting Engine (NSE) service audits to web technology fingerprinting, virtual host (vhost) fuzzing, and client-side source code intelligence gathering, these labs offer real-world exercises to refine your reconnaissance skills.

---

## Lab Collection & Index

Below is the complete, searchable index of all reconnaissance and enumeration challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Morpheus Mirror: Web Technology Fingerprinting** | Web Reconnaissance | Technology stack identification, Wappalyzer/WhatWeb usage, CMS detection | [Access Lab](https://learn.secbyte.org/ctf/morpheus-mirror-web-technology-fingerprinting) |
| 2 | **HTTP Header Analysis - Matrix Breakout 2: Morpheus** | Web Reconnaissance | HTTP response headers, server banners, security flag inspection | [Access Lab](https://learn.secbyte.org/ctf/http-header-analysis-matrix-breakout-2-morpheus) |
| 3 | **Virtual Host Enumeration - Matrix Breakout Morpheus** | Web Reconnaissance | Vhost brute-forcing, Host header manipulation, sub-domain discovery | [Access Lab](https://learn.secbyte.org/ctf/virtual-host-enumeration-matrix-breakout-morpheus) |
| 4 | **Matrix Breakout 2: Morpheus Directory & File Fuzzing** | Web Fuzzing | Directory brute-forcing, file extension discovery, Gobuster/FFUF usage | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-directory-file-fuzzing) |
| 5 | **Matrix Breakout 2: Morpheus Source Code Intelligence Gathering** | Source Analysis | HTML comment review, developer hints extraction, JavaScript analysis | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-source-code-intelligence-gatherin) |
| 6 | **Matrix Breakout 2: Morpheus robots.txt & Hidden Resources Discovery** | Web Reconnaissance | Disallowed path inspection, hidden directory identification, crawling | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-robots-txt-hidden-resources-disco) |
| 7 | **HTTP Enumeration Fundamentals - Morpheus** | Web Reconnaissance | Basic HTTP verbs, status code evaluation, response parsing | [Access Lab](https://learn.secbyte.org/ctf/http-enumeration-fundamentals-morpheus) |
| 8 | **Matrix Breakout: Morpheus Service Enumeration** | Service Enumeration | Service versioning, banner grabbing, open port verification | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-morpheus-service-enumeration) |
| 9 | **Advanced Nmap Scripting Engine on Morpheus** | Network Enumeration | Nmap NSE scripts (`--script`), vulnerability scanning, protocol audits | [Access Lab](https://learn.secbyte.org/ctf/advanced-nmap-scripting-engine-on-morpheus) |
| 10 | **Matrix Breakout: Professional Nmap Enumeration** | Network Enumeration | Comprehensive port scanning, stealth scans (`-sS`), service identification | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-professional-nmap-enumeration) |
| 11 | **Morpheus Network Echoes: Host Discovery (ARP & ICMP)** | Network Discovery | Layer 2/3 discovery, ARP scanning (`netdiscover`), ICMP sweep (`fping`) | [Access Lab](https://learn.secbyte.org/ctf/morpheus-network-echoes-host-discovery-arp-icmp) |
| 12 | **Matrix Breakout: Network Discovery Fundamentals** | Network Discovery | Subnet mapping, host identification, network environment profiling | [Access Lab](https://learn.secbyte.org/ctf/matrix-breakout-network-discovery-fundamentals) |

---

## Categories

### 1. Network Discovery & Service Auditing
Learn to identify live hosts on local subnets, perform port sweeps, and leverage the Nmap Scripting Engine (NSE) to detect target service vulnerabilities.
- [Matrix Breakout: Network Discovery Fundamentals](https://learn.secbyte.org/ctf/matrix-breakout-network-discovery-fundamentals)
- [Morpheus Network Echoes: Host Discovery (ARP & ICMP)](https://learn.secbyte.org/ctf/morpheus-network-echoes-host-discovery-arp-icmp)
- [Matrix Breakout: Professional Nmap Enumeration](https://learn.secbyte.org/ctf/matrix-breakout-professional-nmap-enumeration)
- [Advanced Nmap Scripting Engine on Morpheus](https://learn.secbyte.org/ctf/advanced-nmap-scripting-engine-on-morpheus)
- [Matrix Breakout: Morpheus Service Enumeration](https://learn.secbyte.org/ctf/matrix-breakout-morpheus-service-enumeration)

### 2. Web Application & Protocol Reconnaissance
Discover web server configuration details, inspect HTTP response structures, and identify the underlying server technology stack.
- [HTTP Enumeration Fundamentals - Morpheus](https://learn.secbyte.org/ctf/http-enumeration-fundamentals-morpheus)
- [HTTP Header Analysis - Matrix Breakout 2: Morpheus](https://learn.secbyte.org/ctf/http-header-analysis-matrix-breakout-2-morpheus)
- [Morpheus Mirror: Web Technology Fingerprinting](https://learn.secbyte.org/ctf/morpheus-mirror-web-technology-fingerprinting)
- [Matrix Breakout 2: Morpheus Source Code Intelligence Gathering](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-source-code-intelligence-gatherin)

### 3. Attack Surface Mapping & Content Fuzzing
Fuzz web servers to uncover unlinked directories, hidden virtual hosts, disallowed crawling paths, and sensitive files.
- [Matrix Breakout 2: Morpheus robots.txt & Hidden Resources Discovery](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-robots-txt-hidden-resources-disco)
- [Virtual Host Enumeration - Matrix Breakout Morpheus](https://learn.secbyte.org/ctf/virtual-host-enumeration-matrix-breakout-morpheus)
- [Matrix Breakout 2: Morpheus Directory & File Fuzzing](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-directory-file-fuzzing)

---

## Learning Path

Follow this structured workflow to master target discovery and reconnaissance:

1. **Phase 1: Subnet Host Discovery** — Identify active IP addresses on the network segment:
   - [Matrix Breakout: Network Discovery Fundamentals](https://learn.secbyte.org/ctf/matrix-breakout-network-discovery-fundamentals)
   - [Morpheus Network Echoes: Host Discovery (ARP & ICMP)](https://learn.secbyte.org/ctf/morpheus-network-echoes-host-discovery-arp-icmp)

2. **Phase 2: Port & Service Enumeration** — Scan target hosts to discover open ports and service details:
   - [Matrix Breakout: Professional Nmap Enumeration](https://learn.secbyte.org/ctf/matrix-breakout-professional-nmap-enumeration)
   - [Matrix Breakout: Morpheus Service Enumeration](https://learn.secbyte.org/ctf/matrix-breakout-morpheus-service-enumeration)
   - [Advanced Nmap Scripting Engine on Morpheus](https://learn.secbyte.org/ctf/advanced-nmap-scripting-engine-on-morpheus)

3. **Phase 3: Web Server & Tech Stack Identification** — Analyze target web servers and header responses:
   - [HTTP Enumeration Fundamentals - Morpheus](https://learn.secbyte.org/ctf/http-enumeration-fundamentals-morpheus)
   - [HTTP Header Analysis - Matrix Breakout 2: Morpheus](https://learn.secbyte.org/ctf/http-header-analysis-matrix-breakout-2-morpheus)
   - [Morpheus Mirror: Web Technology Fingerprinting](https://learn.secbyte.org/ctf/morpheus-mirror-web-technology-fingerprinting)

4. **Phase 4: Deep Content & Endpoint Fuzzing** — Map out virtual hosts, hidden directories, and source intelligence:
   - [Matrix Breakout 2: Morpheus robots.txt & Hidden Resources Discovery](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-robots-txt-hidden-resources-disco)
   - [Matrix Breakout 2: Morpheus Source Code Intelligence Gathering](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-source-code-intelligence-gatherin)
   - [Virtual Host Enumeration - Matrix Breakout Morpheus](https://learn.secbyte.org/ctf/virtual-host-enumeration-matrix-breakout-morpheus)
   - [Matrix Breakout 2: Morpheus Directory & File Fuzzing](https://learn.secbyte.org/ctf/matrix-breakout-2-morpheus-directory-file-fuzzing)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Review the scenario instructions on the [Learn SecByte](https://learn.secbyte.org/) lab interface.
3. Deploy your preferred terminal tools (e.g., `nmap`, `netdiscover`, `gobuster`, `ffuf`, `curl`) within your local attack machine or lab environment.
4. Execute systematic reconnaissance methodology, record discovered resources, and retrieve validation flags.

---

## Disclaimer

This repository and its linked challenge resources are created exclusively for educational, authorized training, and security research purposes. Unauthorized scanning, testing, or exploitation of computer systems without explicit written permission is strictly prohibited.
