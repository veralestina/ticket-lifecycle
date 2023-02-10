<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Creating a Ticket
- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
- The Lifecycle of a ticket begins with the opening of a ticket. To do this we will go to the Support Center page and click on Open a New Ticket.
<p>
<img src="https://github.com/veralestina/Images/blob/main/Github%20information/ostciketopennewticket.png" height="50%" width="50%" alt="opennewticket"/>
</p>
<p>
We will use one of the Users that we previoulsy created and describe our issue. 

<p>
<img src="https://github.com/veralestina/Images/blob/main/Github%20information/openanewticket.png" height="50%" width="50%" alt="opennewticket"/>
</p>

Now, the most common issues for Help Desk are:
- Passwords/Credential issues or Login issues
- Access Provisioning - Access is denied
- Equipment Processing - equipment is new issue/returned/lost/stolen
- Something broke or has stopped working
- Software install needed or upgrade needed
- Missing/Deleted Document or Email
- Computer/Internet is slow
- Cannot print/Printer setup/Printer Issue
- VPN/Connectivity Issues
- Clicked a bad link/Malware

Each of these issues is a common real-world problem.

Open a new ticket for each of the above issues. Go to  http://localhost/osTicket/  to open a new ticket for each of the issues listed above.

Go back to http://localhost/osTicket/scp/login.php  
Log back in using useradmin credentials.
Click on the admin panel. Should see the newly opened tickets listed with each of the issues.
Using the SLA created previously;
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
We will sort the tickets based on their severity impact to the company.

Now some of these depend on who or what a person's job is when assessing the severity of the issue's impact on the company still being able to function. A password/credntial issue is bad for all users but especially bad for someone who is charge of customer facing responsibilities, meaning that customer facing tasks can't get done.
An equipment processing ticket can be a low impact or high impact depending on the job and whether or not the equipment stolen or lost had valuable data on it.

Go through each ticket and work them.
Go back to the admin login page and type in one of the Agent's username and password.
In the Agent Panel, click on Tickets tab, the open tickets should be listed.

Below is how to solve;
- Passwords/Credentials can't login. This would use Active Directory, either unlock or reset.
- Access Provisioning. This needs to verify user and give access.
- Equipment Processing. This would follow the procedure put in place by the company. Paperwork.
- Something is broken or stopped working. This would be escalated to the correct team.
- Software install or upgrade. Requires authorization for the user.
- Missing/Deleted Document or email. This involves microsoft word/excel. Usually found in the autosave cache history.
- Computer/Internet slow. This would use TaskManager to solve.
- Cannot Print/Printer setup. Might require onsite help or simply redownloading printer software.
- VPN/Connectivity issue. May be an issue with the VPN being used or improper use. Troubleshoot it.
- Clicked a bad link/malware. Should utlize the software already available to defend and isolate the malware.

Use the above as a guide to figure out how each open ticket would be classified with the SLA. Sort the tickets by using the SLA to figure out the order in which to respond to the tickets.
Tickets can be assigned to Departments and Agents that were created. 

After the tickets are sorted, respond to each open ticket with clear steps that were taken to resolve the issue.


