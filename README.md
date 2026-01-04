# AD-LAB
# 🧪 Active Directory Home Lab (Windows Server 2022)

## 📌 Overview
This project is a fully virtualized **Active Directory home lab** designed to simulate a real enterprise IT environment. The lab was built on a Linux Mint host using virtualization and includes a **Windows Server 2022 Domain Controller** and a **Windows 11 domain-joined client**.

The purpose of this lab is to gain hands-on experience with **identity management, Group Policy, user administration, and automation**, mirroring common tasks performed by Help Desk and Systems Administrators in production environments.

---

## 🖥️ Lab Environment

### Host System
- **OS:** Linux Mint  
- **CPU:** Intel Core i5-8365U (Quad-Core)  
- **RAM:** 16 GB  
- **Virtualization:** Oracle VirtualBox  

### Virtual Machines
| VM | OS | Role |
|----|----|------|
| DC01 | Windows Server 2022 | Domain Controller (AD DS, DNS) |
| WIN11-CLIENT | Windows 11 | Domain-joined client |

### Networking
- **NAT Adapter:** Internet access  
- **Internal Network:** Isolated domain communication  

---

## 🔐 Active Directory Configuration

- Installed and configured **Active Directory Domain Services (AD DS)**
- Promoted Windows Server 2022 to **Domain Controller**
- Joined Windows 11 client to the domain
- Verified DNS functionality for domain authentication

---

## 👥 Users, Groups & OUs

- Created **domain user accounts**
- Designed **Organizational Units (OUs)** for departments
- Created **security groups** to represent department membership
- Practiced user and group management using **Active Directory Users and Computers (ADUC)**

---

## 🛠️ Group Policy (GPO)

- Configured **Group Policy Objects (GPOs)** to apply department-based desktop settings
- Enforced **department-specific wallpapers** (e.g., Engineering, other departments)
- Restricted users from changing their desktop wallpapers
- Linked GPOs to appropriate OUs to demonstrate scoped policy enforcement

---

## ⚙️ PowerShell Automation

- Used **PowerShell** for basic Active Directory administration tasks
- Automated **Active Directory user password resets**
- Practiced command-line management alongside GUI-based tools

---

## 🧪 Tasks Practiced (Real-World IT Scenarios)

- Domain join troubleshooting
- User account management
- Group-based access control
- GPO enforcement and troubleshooting
- Password resets via PowerShell
- Basic AD administration workflows

---

## 📸 Documentation
Screenshots were captured to validate:
- VM configuration
- Server Manager roles
- Active Directory Users and Computers
- Group Policy Management Console
- Domain join status on Windows 11 client

---

## 🚀 Future Enhancements
- Add DHCP role
- Implement additional Group Policies
- Expand PowerShell automation
- Build Python-based AD audit tools
- Simulate help desk ticket workflows
- Integrate security logging and monitoring

---

## 🧠 Skills Demonstrated
- Windows Server administration
- Active Directory management
- Group Policy configuration
- PowerShell automation
- Virtualization and networking
- Troubleshooting enterprise IT environments

---

## 📄 Resume Summary
> Built a virtualized Active Directory home lab using Windows Server 2022 and Windows 11. Configured AD DS, managed users and groups, implemented Group Policy for department-based restrictions, automated administrative tasks with PowerShell, and simulated real-world IT support workflows.

---

## 📬 Contact
Feel free to reach out if you'd like to discuss this lab, provide feedback, or collaborate.
