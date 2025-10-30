# 🧩 Home IT Help Desk Lab

This project simulates a small company IT environment using **VirtualBox**, **Windows Server 2022**, and **Windows 10** clients.  
It demonstrates real-world help desk and system administration skills, from domain setup to troubleshooting.

---

## ⚙️ Lab Overview

| Role | Hostname | OS | IP | Function |
|------|-----------|----|----|-----------|
| Domain Controller | DC01 | Windows Server 2022 | 10.0.0.10 | Active Directory + DNS |
| Client 1 | Client01 | Windows 10 | 10.0.0.20 | Workstation |
| Client 2 | Client02 | Windows 10 | 10.0.0.21 | Workstation |

Network: **Internal Network – LabNet**

---

## 🧱 Module 1 – Domain Controller Setup

**Reason:**  
Create a centralized directory and authentication system.  

**Action:**  
Installed Windows Server 2022, configured static IP, installed AD DS, and promoted server to domain controller (`techlab.local`).  

**Result:**  
Domain successfully created and logins verified.

**Skills Learned:**  
- Windows Server installation  
- AD DS setup  
- DNS configuration  

📸 `Screenshots/ServerManager_ADDS_Installed.png`  
📸 `Screenshots/Domain_Promotion.png`  
📸 `Screenshots/Server_Login_Domain.png`

---

## 👥 Module 2 – User & Group Management

**Reason:**  
Simulate how IT help desk manages employees and access control.  

**Action:**  
Created OUs (HR, IT, Sales), added users (`jdoe`, `asmith`, `mbrown`), and configured group “PrinterAccess.”  

**Result:**  
Users logged into domain successfully; group membership validated.  

**Skills Learned:**  
- ADUC administration  
- User lifecycle management  
- Security group creation  

📸 `Screenshots/ADUC_OU_Structure.png`  
📸 `Screenshots/ADUC_Users.png`  
📸 `Screenshots/AD_Group_PrinterAccess.png`

---

## 🧩 Module 3 – Group Policy Management

**Reason:**  
Learn to enforce security and configuration rules company-wide.  

**Action:**  
Created GPO `HR_Restrictions` → Disabled Control Panel access for HR users.  

**Result:**  
Policy applied successfully; HR user restricted, IT user unaffected.  

**Skills Learned:**  
- Group Policy creation and linking  
- OU targeting  
- Security hardening  

📸 `Screenshots/GPMC_New_GPO.png`  
📸 `Screenshots/GPMC_ControlPanelPolicy.png`  
📸 `Screenshots/Client01_GPO_Result.png`

---

## 🌐 Module 4 – Network Testing & Troubleshooting

**Reason:**  
Understand how connectivity and DNS affect authentication.  

**Action:**  
Configured static IPs, tested connectivity with `ping` and `ipconfig`, simulated and resolved DNS failures.  

**Result:**  
Verified that DNS and IP configuration directly impact domain login success.  

**Skills Learned:**  
- Network diagnostics  
- DNS troubleshooting  
- Problem isolation  

📸 `Screenshots/Client01_IPCONFIG.png`  
📸 `Screenshots/PING_DC01.png`  
📸 `Screenshots/PING_Fail_And_Fix.png`

---

## 🧰 Module 5 – SysInternals Diagnostics

**Reason:**  
Gain visibility into system performance and potential malware behavior.  

**Action:**  
Used Process Explorer, Autoruns, and TCPView to observe system performance and active network connections.  

**Result:**  
Identified unnecessary startup items and analyzed live system activity.  

**Skills Learned:**  
- Windows diagnostics  
- Process and network monitoring  
- Security awareness  

📸 `Screenshots/ProcessExplorer.png`  
📸 `Screenshots/Autoruns.png`  
📸 `Screenshots/TCPView.png`

---

## 🧾 Module 6 – Documentation and GitHub

**Reason:**  
Showcase work professionally with evidence and clean structure.  

**Action:**  
Documented modules, added screenshots, and uploaded full project to GitHub repository.  

**Result:**  
Portfolio-ready project demonstrating end-to-end IT lab setup and operations.  

**Skills Learned:**  
- Git & GitHub workflow  
- Technical documentation  
- Version control  

📸 `Screenshots/GitHub_Repo_MainPage.png`  
📸 `Screenshots/Git_Command_Push.png`

---

## 💡 Key Takeaways

**Core Skills Developed**
- Windows Server 2022 administration  
- Active Directory & Group Policy management  
- Network configuration and troubleshooting  
- SysInternals analysis  
- IT documentation and version control  

**Example Resume Lines**
- Built and managed a Windows Server–based Active Directory environment with domain users, OUs, and GPOs.  
- Troubleshot domain and DNS connectivity issues using `ping` and `ipconfig`.  
- Documented all findings and configurations on GitHub to showcase hands-on IT experience.

---

✅ **GitHub Repository:**  
[https://github.com/YOURUSERNAME/Home_IT_Lab](https://github.com/YOURUSERNAME/Home_IT_Lab)
