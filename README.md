# Active-Directory and Patch Management with Windows Server 2025
This Hands-on project demostrates the deployment and managemnt of an Active Directory (AD) environment using Windows Server 2025. It covers PowerShell deployment configuration of AD DS, domain configuration, client machine domain joining, Group policy exploration, and centralized patch mangement using Action1.
## Project objectives 
- Deploy AD DS with PowerShell
- Join Widows 11 clients to a domain
- Implement user/group account management
- Explore Group Policies for centralized control
- Demonstrate Patch management with Action1.
Skills Higlighted: Windows Server Administration, Powershell, Active Directory, Group Policy, Patch Management, IT Support, System Administration
## Lab setup
Tools & Environment 
- Hypervisor: VirtualBox
- Server OS: Windows Server 2025 (Domain Controller)
- Client OS: Windows 11
- Domain name: sallylab.com
- Patch Management Tool: Action1
# Implementation Steps
# 1. Active Directory Domain Service deployment using PowerShell
![AD Install Screenshot](screenshots/adds-install.png)
## 2. Join Windows 11 Client to the Domain
- Change the Virtual Machine setting to allow Host only Adapter
- Join the Windows 11 client and Windows server IPv4 to same subnet
![AD Ping Screenshot](screenshots/PingResult.png)
- Steps: system properties > change settings > join domain sallylab.com >Reboot > Login with domain
![AD Domain Screenshot](screenshots/DomainJoin.png)
- Enabled Remote destktop connection > connect via IPv4 address
- 





   
