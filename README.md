<h1>Create Lab Environment Running Actve Directory</h1>


<h2>Description</h2>
In this project I created two virtual machines to serve as my lab environment. The first machine was runnning Windows Server 2019. This allowed me to create a Virtual Local Area Network. I set up  Actice Directory and other services to run on this machine. I also used Powershell to create a list of users in AD. The second machine was set up running Windows 10 Pro. This was confgured as a client and tied into the network through the server. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Oracle Virtual Box</b>
- <b>Windows Server 2019</b>
- <b>Windows 10 Pro</b>

<h2>Program walk-through:</h2>

<p align="center">
Create Windows Server 2019 VM: <br/>
<img src="AD Home Lab/1 Create Server VM.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Configure Active Directory:  <br/>
<img src="AD Home Lab/2 Configure AD.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Add New User in AD Manually: <br/>
<img src="AD Home Lab/3 Add user in AD.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Connect Server to the Internet:  <br/>
<img src="AD Home Lab/4 Connect Server to the Internet.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Configure DHCP Server :  <br/>
<img src="AD Home Lab/5 Configure DHCP server.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Script for using Powershell to add 1000 users to AD:  <br/>
<img src="AD Home Lab/6 Script for creating 1k users.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Run Script in Powershell to create new users:  <br/>
<img src="AD Home Lab/7 Running script to create users.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Create Client VM using Windows 10:  <br/>
<img src="AD Home Lab/8 Create Client VM.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Final Set Up of Domain Controller:  <br/>
<img src="AD Home Lab/9 Final Set up of Domain Controller.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Users Added to AD:  <br/>
<img src="AD Home Lab/10 Users Added to AD.png" height="80%" width="80%" alt="AD Lab Steps"/>
<br />
<br />
Client Terminal Added in AD:  <br/>
<img src="AD Home Lab/11 Client Terminal Added in AD.png" height="80%" width="80%" alt="AD Lab Steps"/>
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
