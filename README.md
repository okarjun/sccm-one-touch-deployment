\# 💻 SCCM One-Touch Laptop Deployment



This project automates zero-touch laptop provisioning using SCCM, PXE boot, and task sequences — enabling fully configured Windows 11 devices in under 1 hour.



\## 🎯 Objective



To eliminate manual setup by automating:

\- PXE-based OS deployment

\- Domain join \& hostname assignment

\- BitLocker encryption

\- USB blocking policies

\- Full SCCM registration



\## ⚙️ Features



\- MAC-to-hostname mapping CSV

\- Task sequence with preconfigured apps \& drivers

\- Auto join to domain OU

\- GPO applied automatically

\- Minimal technician effort



\## 🛠️ Technology Stack



\- SCCM (Current Branch)

\- PowerShell

\- Windows 11 (Build 26100)

\- Active Directory

\- DHCP with PXE helper



\## 📂 Project Structure



| Folder     | Purpose |

|------------|---------|

| `scripts/` | PowerShell automation (join, policy, etc) |

| `docs/`    | SOPs and technical documentation |

| `assets/`  | Screenshots, diagrams |



\## 🧪 Deployment Flow



1\. Map MAC to hostname in CSV

2\. PXE boot laptop on VLAN with SCCM

3\. Task sequence auto-triggers

4\. Device joins domain, gets GPO, security hardening

5\. Ready in under 45–60 mins



\## 📸 Screenshot



!\[PXE Diagram](assets/pxe-diagram.png)



\## 👨‍💼 Author



\*\*Yam Basnet\*\*  

Sr. Technical Specialist — SCCM | Infra | Automation  





