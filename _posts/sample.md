---
title: "TryHackMe - Basic Pentesting Walkthrough"
date: 2026-02-25 00:30:00 +0530
categories: tryhackme beginner
tags: nmap enumeration ssh brute-force
image: /assets/images/tryhackme-basic-pentesting.png  # optional thumbnail
---

This room teaches basic enumeration and privilege escalation on a vulnerable Linux machine.

**Tools used:**
- nmap
- gobuster
- hydra (for brute-force)

**Steps:**

1. **Port Scanning**
   ```bash
   nmap -sC -sV -p- 10.10.10.10
