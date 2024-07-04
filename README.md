<h1>Vulnerability Management (Greenbone OpenVAS)</h1>


<h2>Description</h2>
This project demonstrates the use of Greenbone OpenVAS to scan for vulnerabilities in a deliberately vulnerable Metasploit 2 instance.
<br />

<h2>Overview</h2>
Greenbone OpenVAS (Open Vulnerability Assessment System) is an open-source tool for vulnerability scanning and management. This project involves setting up and configuring OpenVAS to identify security weaknesses in a Metasploit 2 environment, which is intentionally designed to be vulnerable for educational and testing purposes.

<h2>Utilities Used</h2>

- <b>Greenbone OpenVAS</b> 

<h2>Environments Used </h2>

- <b>Windows 10 VM</b> (21H2)
- <b>VMware Workstation</b> 
- <b>Metasploitable2 2</b>

<h2>Program walk-through:</h2>

<p align="center">
Download OpenVAS: <br/>
<img src="https://i.imgur.com/81kpia8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/MYvrLGV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/5IebAvP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Choose the apprpriate option for your VM:  <br/>
<img src="https://i.imgur.com/cLXHxHc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click "instruction" to download OVA file:  <br/>
<img src="https://i.imgur.com/31HrpGS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After Download, Import the OVA file in VMware:  <br/>
<img src="https://i.imgur.com/Nx6b0QG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Y33djcF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change Network Adapter to NAT, for OpenVAS to communicate to Windows VM:  <br/>
<img src="https://i.imgur.com/zYLh91C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch OpenVAS and Login with default credntials (admin/admin):  <br/>
<img src="https://i.imgur.com/C92mecc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Configuration:</h2>

Configure OpenVAS:  <br/>
<img src="https://i.imgur.com/LUCywkk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Yes:  <br/>
<img src="https://i.imgur.com/yqodrRO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click Yes:  <br/>
<img src="https://i.imgur.com/73j1JnI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create web login details:  <br/>
<img src="https://i.imgur.com/BLLwWUB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/tReznP8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Skip:  <br/>
<img src="https://i.imgur.com/228YqNg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Greenbone Running selfcheck:  <br/>
<img src="https://i.imgur.com/2868YPw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click "OK" to update feed:  <br/>
<img src="https://i.imgur.com/MKjhBBZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Perform Maintenance:  <br/>
<img src="https://i.imgur.com/EpxiN1O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Update the feed:  <br/>
<img src="https://i.imgur.com/Gnrrwo9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Je6IQLG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/Xox7UIl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go back  to "About":  <br/>
<img src="https://i.imgur.com/rPaAEm2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm System Status:  <br/>
<img src="https://i.imgur.com/qOMQK4s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Perform Scan:</h2>

Login to web interface with Credentials created:  <br/>
<img src="https://i.imgur.com/Kghnf3i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
OpenVAS Dashboard:  <br/>
<img src="https://i.imgur.com/OnjrRm3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/TyA88Jv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to "Configuration" > "Target" > Create New Target:  <br/>
<img src="https://i.imgur.com/2HEjNVK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Input IP  address:  <br/>
<img src="https://i.imgur.com/TiihQrV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm scan details:  <br/>
<img src="https://i.imgur.com/lymDxBr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to "Scans" > "Tasks" > "New Tasks" > Create a New Task:  <br/>
<img src="https://i.imgur.com/uJRMq6k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run Scan:  <br/>
<img src="https://i.imgur.com/BouRZbk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/EIsrz73.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Scan Results:</h2>

Scan Results:  <br/>
<img src="https://i.imgur.com/6iP9QRe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
View Scan Results in detail:  <br/>
<img src="https://i.imgur.com/WA9Oxmj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/YLqnXXz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/0thXQm6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/12UdhyM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/RM7S14D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Note:</h2>
The vulnerabilities identified in this project are not remediated, as the Metasploit 2 instance is configured to be vulnerable intentionally.

<h2>Conclusion:</h2>
This project serves as a practical demonstration of using Greenbone OpenVAS for vulnerability scanning, providing valuable insights into the capabilities of the tool and the types of vulnerabilities it can detect.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
