<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/dtqDg6d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create two virtual machines in Azure, one Windows and one Linux, in the same region and virtual network.
</p>
<br />

<p>
<img src="https://i.imgur.com/dMhWIB1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Access both virtual machines using Remote Desktop. Enter the IP address, user name, and password you created to log in successfully. 
</p>
<br />

<p>
<img src="https://i.imgur.com/iAsIOyT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use Wireshark to track ICMP and SSH traffic by pinging a virtual machine and observing the response. Specify ICMP/SSH in Wireshark's search bar to filter the results. 
</p>
<br />
