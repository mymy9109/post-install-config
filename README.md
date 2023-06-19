<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Teams
- Configure Agents(Workers)
- Configure Users(Customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/5GgXc8C.png"/>
</p>
<p>
To be able to create and configure roles you have to log in then make sure you are in the admin panel to know if you are top right you it will say agent pane, profile or log out. Then you will go to agents and creat new role in there you can choose what access you want a specific person to have. 
</p>
<br />

<p>
<img src="https://i.imgur.com/GALAiJ9.png"/>
</p>
<p>
In this step you see we are adding and configuring a new teams. The two teams i created was level | support and level || support which i did under the admin pane.Then selected agents then created my new two teams. 
</p>
<br />

<p>
<img src="https://i.imgur.com/HC5owsC.png"/>
</p>
<p>
Then we created SLA which is how much time the administrator expect a ticket to be closed. To do this we had to be in admin pan under manage then choose SLA create new. We created threen different SLA. 
  SEV-A 1 hour in 24/7
  SEV-B 4 Hours in 24/7
  SEV-C 8 Hours in Monday-Friday 8am-5pm with US Holidays
</p>
<br />
