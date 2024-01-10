# ticket-lifecycle

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- IIS
- OSTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

![Screenshot 2024-01-03 162140](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/ec00d97a-6eaf-4f25-afc4-894c48bc48a7)
![Screenshot 2024-01-03 162227](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/a65c2700-c7f1-4599-855a-7005c2b0c447)
![Screenshot 2024-01-03 162446](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/c07f0d90-e429-4963-9a45-8cafad2288c8)
![Screenshot 2024-01-03 163159](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/07619a42-dc38-4c0e-848e-a74dba718cf5)
![Screenshot 2024-01-08 141411](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/8a62aa45-82e5-48e8-8975-a675bb04967b)




First since we are using a virtual machine for this turtorial . We will go to Portal.azure.com > create a resourse group > Virtual machines > copy the i.p address > use remote desktop ( or a mac equilant ) to sign into the desktop that we created

</p>
<br />

![Screenshot 2024-01-09 133654](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/23cd8579-1af3-45fe-a9ff-e855752c6b9b)

We will login to osTicket with whatever your Credientials is.

![Screenshot 2024-01-10 140840](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/74d7cc98-c77f-40fb-86e9-4f42e4e33673)

To start creating tickets we will be going to http://localhost/osTicket/ and it should bring up your local server osTicket that we have previously created in the previous tutorial. 

![Screenshot 2024-01-10 142521](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/8b176d6a-b54b-475f-8861-78113f753c64)
![Screenshot 2024-01-10 142805](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/44416bdb-a51c-47a9-9d56-161a1725e9d9)
![Screenshot 2024-01-10 141825](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/18827579-c9ca-4227-9d94-9d3ea5d371f5)


We will click the blue bar "Open a New Ticket"> Fill out the contact form > Create Ticket >. I will create a few random tickets.

![Screenshot 2024-01-10 143003](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/dd396bca-ad65-4806-b790-6db1c20a2a7f)

Now we will login to help desk as "AGENT" and solve the tickets. We will go to localhost/osTicket/scp.login.php.

![Screenshot 2024-01-10 143119](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/2ab7f84d-7804-4324-9c83-f6a4b88baf4f)
![Screenshot 2024-01-10 143607](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/a40bde39-e282-404f-b110-e0d968e02e48)



After login   you will see some Tickets and we will go ahead and solve them as if we are in a real world scenario. ( Depending on the Agents Permissions given to the Agents in the previous tutorial you may or may not be able to see the tickets but this is all done in the Admin Panel > Agents > Agents > Permissions )

![Screenshot 2024-01-10 144304](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/2c108149-75d5-45b8-86f9-96af7806fa9c)
![Screenshot 2024-01-10 144445](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/6a0906ce-0591-4a9c-97fe-65591cbeff18)
![Screenshot 2024-01-10 144527](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/e83a2b26-8717-4b04-a0f2-988081bc62aa)


We will click a Ticket and set the "SLA" ( Service Level Agreement ) , "Priorty" , "Department" , Status and respond to the user. Click the ticket > Status > priority > Department > SLA Plan 

![Screenshot 2024-01-10 145115](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/0b91928b-7de3-46e3-bee0-e51b2b40fc55)
![Screenshot 2024-01-10 145238](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/9d7ffa15-e4c4-40e5-ae47-6a9ede19571d)


You can assign the ticket to a  team or agent and respond to the user.

![Screenshot 2024-01-10 145548](https://github.com/kevonrochester/ticket-lifecycle/assets/155024615/81b65dbf-0363-4e6c-993f-39bf9e991308)

And "Resolved" or "CLosed" Tickets will be moved to Agent Panel > Tickets > Closed. This concludes the tutorial.

