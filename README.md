<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
Project outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents & Users
- Configure SLA and Help Topics

<h2>Configuration Steps</h2>
<p align="center">
Open the Web Browser, navigate to http://localhost/osTicket/scp/login.php and login to osTicket using the username/password: Adminuser/Password1
  
![image](https://github.com/user-attachments/assets/69b7c61f-5a56-415c-a4ac-840a639560b0)


<p align="center">
Configuring Roles: In the Admin Panel, click "Agents", then "Roles", and then "Add New Role":

![image](https://github.com/user-attachments/assets/c983aef0-78ad-4d83-9795-3f64ab282e87)

<p align="center">
Name the Role: "Supreme Admin", and under "Permissions", check all the Tickets and Tasks in order to give this role "Supreme" access:

![image](https://github.com/user-attachments/assets/06b3c303-c8f9-45a9-835d-a2b493207120)

![image](https://github.com/user-attachments/assets/97969b08-83f5-4e6d-ae0d-97a38c6f724c)
<p align="center">
In the same fashion, you can configure various Teams and Departments and give each various access.  Once Roles, Teams, and Departments are configured, you can add new Agents, assign them Access/Departments and Permissions and add them to a Team:

![image](https://github.com/user-attachments/assets/8dacfa14-1b15-4f0f-aa2a-77e095b38915)

<p align="center">
Configuring SLA's and Help Topics:  Under the Manage tab, you can add new SLA Plans to assign a severity level to created tickets.  Additionally, under Help Topics, you can create various topics for created tickets:

![image](https://github.com/user-attachments/assets/4d8ef2e8-9452-4173-8bf6-17dc9c598628)

![image](https://github.com/user-attachments/assets/cc6c3f5d-6c3c-466c-a01e-2f594463a2af)

<h2>osTicket Setup Complete!</h2>









