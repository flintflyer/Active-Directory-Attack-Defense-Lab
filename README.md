<h1>Active Directory Attack Detection & Threat Hunting Lab</h1>



<h2>Description</h2>
Project consists of a virtual Active Directory Lab where I initiated a Brute Force attack using Hydra, monitored logs through Microsoft Sentinel as well as 
developed an alert system to report the ongoing incidents.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Hydra</b> 
- <b>Bash</b>
- <b>Wordlists</b>
- <b>Nmap</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Kali Linux</b>
- <b>Windows 11 </b>

<h2>Program walk-through:</h2>

<p align="center">
Initiate Hydra Brute Force Attack: <br/>
<img src="https://i.imgur.com/pE3zifv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The chart '4625' represents Hydra rapidly trying new passwords:  <br/>
<img src="https://i.imgur.com/KJJTH2C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Excessive login attempts will trigger an alert: <br/>
<img src="https://i.imgur.com/E4egWvh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Rule Saved and waiting for incoming incident:  <br/>
<img src="https://i.imgur.com/8396XFM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Hydra Attack delivered 440 attempts in 15 minutes :  <br/>
<img src="https://i.imgur.com/DCHP7LA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Alert of log-on failure attempt and event ID '4625':  <br/>
<img src="https://i.imgur.com/sJysjGZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
