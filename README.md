# IT Support and Administration Lab (Active Directory)

## Overview
This repository documents the deployment and administration of a Windows Server 2022 Active Directory environment designed to reflect real-world IT support operations. The lab focuses on practical, hands-on tasks commonly performed in IT environments, including user account management, domain administration, Group Policy configuration, Windows client management, and patch management.

The same environment is reused and expanded across all labs to simulate how systems are managed over time.

---

## Lab Environment

| Component | Details |
|---|---|
| Virtualization | Oracle VirtualBox |
| Server OS | Windows Server 2022 (Desktop Experience) |
| Client OS | Windows 11 Pro |
| Domain Name | corp.local |
| Domain Controller | DC01 |
| Patch Management | Action1 (free tier) |

---

## Lab Breakdown

Each lab folder includes step-by-step documentation and screenshots demonstrating configuration and validation.

| Lab | Topics Covered |
|---|---|
| [Lab 01: Environment Setup](./01-environment-setup/) | Windows Server 2022 installation, virtual machine setup, AD DS role installation, Domain Controller promotion, domain creation |
| [Lab 02: User Account Management](./02-user-account-management/) | User provisioning, OUs, password resets, account lockout, offboarding procedures |
| [Lab 03: Domain Join and Remote Access](./03-domain-join-and-rdp/) | Windows 11 setup, static IP configuration, DNS configuration, domain join, RDP |
| [Lab 04: Group Policy](./04-group-policy/) | Password policy, account lockout policy, desktop restrictions, wallpaper enforcement, user privilege controls |
| [Lab 05: File Shares and Permissions](./05-file-shares-and-permissions/) | NTFS permissions, shared folders, security groups, access control |
| [Lab 06: Patch Management](./06-patch-management/) | Action1 deployment, asset inventory, CVE identification and remediation |

---

## Skills Demonstrated

- Active Directory deployment and Domain Controller configuration
- User account lifecycle management (provisioning, password resets, lockouts, offboarding)
- Windows 11 domain join and DNS configuration
- Group Policy Object (GPO) creation and enforcement
- Shared folder permissions and access control
- Patch management and CVE remediation using Action1
- Help desk troubleshooting workflows
