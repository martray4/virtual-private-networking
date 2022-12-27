<p align="center">
<img src="https://i.imgur.com/AYrwtEI.png"/>
</p>

<h1>VPN Setup and Usage (Proton VPN)</h1>
This tutorial outlines how to setup a vpn inside of an Azure virtual machine.<br />


<h2>
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>VPN Setup Stages</h2>

- Find your local VPN
- Install your VPN
- Open and Log into VPN
- Select Country you are connecting to

<h2>Setup Stages</h2>

<p>
<img src="https://i.imgur.com/ckgi30f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to your browser type in "what is my IP address.com" in the search bar. Take note of whatever your "IPv4" is, as well as your city. Next step, is to create your virtual machine in azure and connect to it with remote desktop. Then finally you will paste the public IP address of your newly created remote desktop connection. 
</p>
<br />

<p>
<img src="https://i.imgur.com/v9ctD5Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you want to go to your browser from your remote desktop and type in, "whatismyIPaddress.com" and copy your new IPv4 address and citywithin your virtual machine (copy your virtual machine without any vpn) then sign into protonvpn.com and set up an account using local computer. Then you will copy the URL into your remote desktop, and inside your virtual machine you will install the windows VPN client, and simply login. 
</p>
<br />

<p>
<img src="https://i.imgur.com/7vSfdxb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now you have made a connection and connected to a VPN server in Tokyo, Japan and its IP address will reflect that.
</p>
<br />
