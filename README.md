# osTicket-Prerequisites-and-Installation

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source helpdesk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

<ul>
<li>Microsoft Azure</li>
<li>Virtual Machine</li>
<li>osTicket Installation Files</li>
</ul>

<h2>Installation Steps</h2>

<p>
<h3>Step 1: Connect to Your Virtual Machine with Remote Desktop</h3>


<h3>Step 2: Install and Enable Internet Information Services (IIS) in Windows</h3>

- At the bottom left, search for Control Panel
- Underneath Programs, select Uninstall a Program
- On the left side of the screen, select Turn Windows Features On or Off
- Select Internet Information Services (IIS), and select OK


<p align="center">
<img src="https://i.imgur.com/NbQvYeL.png.png" height="80%" width="80%" alt="Azure Free Account"/> 
</p>


<h3>Step 3: Download, Install, and Open the Web Platform Installer
</h3>

- osTicket Installation Files [link](https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6)
	- Download Web Platform Installer > select Download Anyway > at the top right, select Open File
	- Follow the prompt to install Web Platform Installer
	- Open the Web Platform Installer

<p align="center">
<img src="https://i.imgur.com/0On2vKd.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/V4p94mP.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>

- Once Web Platform Installer is open, go to the top right of the screen and search for MySQL 5.5
- Go to MySQL Windows 5.5 and click Add
- Go to the top right again and search for PHP
	- Adjust the list to Sort by "name"
- Add all simple versions of x86 PHP up until 7.3
- Select Install at the bottom of the screen and it will tell you to create a username and password to complete the installation

<p align="center">
<img src="https://i.imgur.com/uWAVcRG.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/MQmZfht.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>


  - Username: root
  - Password: Password1
- Follow the prompt to complete the installation
- You might get a message stating that "some products have failed to install"
	- Ignore that message and select Finish
- Download and install the following from within the lab files: [link](https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6)
  - PHP Version 7.3.8
  - PHP Manager 1.5.0 for IIS 10
  - Microsoft Visual C++ 2009 Redistributable Package


<p align="center">
<img src="https://i.imgur.com/zAPFRmU.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/DUiyQdt.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 4: Install osTicket v1.15.8</h3>
     
