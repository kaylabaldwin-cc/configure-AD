<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com/watch?v=AtAb_8Av4iU)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup resources & virtual machines in Azure
- Ensure Connectivity between the client and Domain Controller
- Install Active Directory
- Create an Admin and Normal User Account in AD

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/rYVJNxe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup both virtual machines (Windows server and Windows 10) on Azure and connect both to Remote Desktop. Connect Client 1 to RD first and ping Domain controller's private IP address in Command Prompt. You'll notice "request timed out" due to DC's firewall ICMP4 settings. Login to remote desktop via DC's public IP address, enable firewall protocols and notice the ping from Client-1 was successful.
</p>
<br />

<p>
<img src="https://i.imgur.com/jc72Kv3.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Active Directory
</p>
<br />

<p>
<img src="https://i.imgur.com/f0QgSnT.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create an Admin and Normal User Account in Active Directory
</p>
<br />
