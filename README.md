<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Provisioning VMs, Editing Network Security Groups (NSGs) and Inspecting Traffic Using Wireshark</h1>
This project covered several Azure fundamentals, including using Remote Desktop and Powershell to remotely connect to VMs I created; then also installing Wireshark on one of these in order to examine traffic of different protocols between the two machines. I also edited the inbound security rules on the NSG in order to block traffic by specifiic protocol types. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Powershell and various Command-Line Tools (some Linux)
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Ubuntu Server 20.04

<h2>Overview</h2>

- Step 1: creating resource group; storage account and blob container
- Step 2: creating Windows VM and Linux VM (Ubuntu) on the same region, vNet and subnet
- Step 3: remote connect to VM1 and install Wireshark
- Step 4: from VM1, ssh into VM2 and observe traffic flows (ICMP, SSH, DHCP, DNS, RDP)

<h2>Actions and Observations</h2>

![image](https://github.com/lcccodes/azure-network-protocols/assets/171904823/84fce06a-00b7-4b45-8e89-8c273eaf3c98)

<p>
[above]: Creating a resource group, storage account and blob container.
</p>
<br />

![image](https://github.com/lcccodes/azure-network-protocols/assets/171904823/68a72aa4-eaf9-457b-b6a3-973989e1ef58)

<p>
[above]: Results of having created two virtual machines, each with its associated resources (NSGs, vNets).
</p>
<br />

![image](https://github.com/lcccodes/azure-network-protocols/assets/171904823/ed7cb197-67ef-43c4-bc9f-07690057d486)


<p>
[above]: Connecting from local machine into Windows VM (public IP) via Remote Desktop.
</p>
<br />
