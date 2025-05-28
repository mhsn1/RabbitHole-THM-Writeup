# TryHackMe: Rabbit Hole Walkthrough — Full Exploit & Capture-the-Flag Guide

## 🔍 Challenge Overview

**Platform:** TryHackMe  
**Room Name:** Rabbit Hole  
**Category:** Web Exploitation, SQL Injection, Enumeration, Processlist Abuse  
**Difficulty:** Intermediate  

**Keywords for SEO:** tryhackme rabbit hole writeup, second-order sqli, processlist mysql exploit, ssh login sql injection, sql injection challenge solution, CTF walkthrough rabbit hole, information_schema processlist attack, MySQL md5 password capture, ethical hacking SQLi lab

> This is a complete, step-by-step professional walkthrough to solve the "Rabbit Hole" room on TryHackMe. It includes command-line tools, Python automation scripts, payloads, and final shell access to capture the flag.

---

## 🛠 Step 1: Initial Reconnaissance

```bash
nmap -T4 -n -sC -sV -Pn -p- 10.10.173.12

Discovered Open Ports:

22/tcp (SSH)

80/tcp (HTTP)

Visit:

```bash
http://10.10.173.12
