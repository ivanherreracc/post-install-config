# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This walkthrough will outline the post installation for osTicket system.
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

-Configure Roles

-Configure Departments

-Configure Teams

-Allow anyone to create tickets

-Configure Agents (workers)

-Configure Users (customers)

-Configure SLA(service level agreement)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/PfHIvVU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once osTicket system is installed open login: http://localhost/osTicket/scp/login.php
</p>
<br />

<p>
<img src="https://i.imgur.com/04moKFb.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/gzk02Od.png" height="45%" width="45%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/f8WQjSP.png" height="45%" width="45%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles
Admin Panel -> Agents -> Roles
Make role of Supreme Admin
,check all permissions for supreme admin

</p>
<br />

<p>
<img src="https://i.imgur.com/7sWVFJK.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/rPdiJXt.png" height="45%" width="45%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments
Admin Panel -> Agents -> Departments
Then Create new System Administrators depart.

</p>
<br />

<p>
<img src="https://i.imgur.com/x5RBSV8.png" height="65%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/eLVigjF.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams

Create two teams

-Level I Support

-Level II Support

</p>
<br />

<p>
<img src="https://i.imgur.com/1KGgdn8.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets

Admin Panel -> Settings -> User Settings

Registration Required: Check require registration and login to create tickets

</p>
<br />

<p>
<img src="https://i.imgur.com/VlpWZ3p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Configure Agents (workers)

  Admin Panel -> Agents -> Add New

-use any name applicable in add new agents.

</p>
<br />

<p>
<img src="https://i.imgur.com/JQfH1c1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)

  Agent Panel -> Users -> Add New

-use any name applicable in add new users.

</p>
<br />

<p>
<img src="https://i.imgur.com/HrjsxUh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA

  Admin Panel -> Manage -> SLA


</p>
<br />
<img src="https://i.imgur.com/cpGgtYd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

</p>
<p>
Next you can select Name, Grace period, and schedule. Once thats filled out and saved you have completed the list of prerequisites.
</p>
<br />

