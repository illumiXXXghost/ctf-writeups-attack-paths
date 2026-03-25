# CTF Writeups & Attack Paths

This repository documents my exploitation process across TryHackMe and HackTheBox machines.  
Each writeup is structured around real attack paths and mapped to the Cyber Kill Chain to show how attackers move, think, and escalate inside a target environment.

These writeups are not simple walkthroughs — they are reconstructions of my attacker mindset as I enumerate, exploit, escalate, and analyze detection opportunities.

---

## 🔥 Purpose of This Repository

To demonstrate:
- My ability to think like an adversary  
- My understanding of reconnaissance, enumeration, exploitation, and privilege escalation  
- My ability to map attacks to the Cyber Kill Chain  
- My growth as a Junior Penetration Tester and SOC Analyst  
- My ability to document findings clearly and professionally  

---

## 🧠 My Writeup Structure

Every writeup follows a consistent, repeatable format:

### **1. Reconnaissance**
What I saw first.  
What the surface looked like.  
What responded.

### **2. Enumeration**
What I discovered.  
Services, versions, directories, users, misconfigurations.

### **3. Exploitation**
How I gained initial access.  
Payloads, scripts, CVEs, manual exploitation.

### **4. Privilege Escalation**
How I moved from user → root/system.  
Weak permissions, SUID, kernel exploits, misconfigurations.

### **5. Detection Opportunities**
Where a SOC could have caught the attack.  
Log artifacts, alerts, anomalies.

### **6. Lessons Learned**
What I internalized.  
How this attack fits into my broader methodology.

---

## ⚡ My Cyber Kill Chain (Personal Interpretation)

I use this chain to understand not just *what* I did, but *why* each step mattered.

1. **Reconnaissance** – Identify the surface.  
2. **Weaponization** – Prepare the tool or exploit path.  
3. **Delivery** – Get the exploit to the target.  
4. **Exploitation** – Trigger the vulnerability.  
5. **Installation** – Establish a foothold or shell.  
6. **Command & Control** – Stabilize, pivot, maintain access.  
7. **Actions on Objectives** – Escalate, extract, dominate.

---

## 📁 Repository Structure
/tryhackme/
<room-name>.md

/hackthebox/
<machine-name>.md

/methodology/
cyber_kill_chain.md
enumeration_checklist.md
exploitation_notes.md
privesc_notes.md

/screenshots/
thm/
htb/



---

## 🚀 Next Steps

I will continue adding:
- TryHackMe room writeups  
- HackTheBox machine writeups  
- Attack path diagrams  
- Enumeration and exploitation notes  
- Screenshots and artifacts  

This repository will grow as I grow — documenting my evolution from student to attacker to professional.

