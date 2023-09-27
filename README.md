<h1>Active Directory Home Lab</h1>

<!-- ### [YouTube Demonstration]()
--!>

<h2>Description</h2>
I used VirtualBox to setup an Active Directory environment. I created a Server and Client virtual machine, configured AD, DHCP and NAT, and joined the Client machine to the domain. I used a powershell script to create multiple users and logged into the Client machine with those users. 
<br/>
I had to troubleshoot issues along the way, starting with actually getting the VMs to work by changing the BIOS settings on my host machine to allow virtualization. I then ran into issues with the Server OS installation and had to increase the drive space I had allocated to the VM. When preparing for the Client machine, I had to download a Windows 10 ISO, but Microsoft would only give me access to the Media Creation tool. To get the ISO, I used Chrome's developer tools to set my user agent as a blackberry OS, which prompted Microsoft to offer the ISO download. Finally, upon joining the Client to the domain, I found that I was not connecting to the internet because my network settings had a typo.
<br/>
Upon completing setup, I implemented a few security policies. I reduced IP lease times to 2 hours from 8 days. I set up password policies requiring 10 characters and complexity including upper and lowercase letters, numbers and special characters. Finally, I set user passwords to reset on next login and configured them to expire every 60 days.
<br/>


<h2>Languages and Utilities Used</h2>

- <b>VirtualBox</b>
- <b>Active Directory</b>
- <b>Powershell</b>

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b>

<!--
<h2>Program walk-through:</h2>

<p align="center">
Launch VirtualBox: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
Create Server VM:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Active Directory: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Domain Admin:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Instll NAT:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Setup DHCP server:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Users:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Windows 10 VM:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Join Windows 10 VM to Domain:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm Internet Access:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
--!>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
