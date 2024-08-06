<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Logon Banner</h1>
This tutorial outlines the implementation of deploying Logon Banner in Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Logon Banner](https://youtu.be/cG7M3Z-Cek4)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

  

<h2>Operating Systems Used </h2>

- Windows Server 2022

<h2>High-Level Deployment and Configuration Steps</h2>

- Run active directory
- Create a new GPO called 'Interactive Login Banner'
- Enable two Interactive Logon Msgs 
- Verify change was made



<h2>Deployment and Configuration Steps</h2>

<p>
<img src="" height="80%" width="80%""/>


</p>
<p>
Diagram
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/fb0afe9b-7b0d-478e-852b-38e5a7b95231" height="80%" width="80%""/>
</p>
<p>
Created a new GPO in mycybercat.com domain called 'Interactive Logon Banner'
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/7fca2e27-9e74-4162-8c5d-efa651823438" height="80%" width="80%""/>
  <img src="https://github.com/user-attachments/assets/c7abd5d1-13f5-4ef3-aa1f-837ec77d5f44" height="80%" width="80%""/>
</p>
<p>Using Security Options to enable Interactive Logon Msgs for Users Attenpting to Logon. Also using Msgs text for users attempting to logon.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/21deffcc-5e6f-4f38-8c81-7ae40d3a204b" height="80%" width="80%""/>
</p>
<p>
Logged into account and can verify that change was made.
</p>
<br />
