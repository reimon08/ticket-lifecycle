<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Prerequisites</h2>

- [osTicket: Installation](https://github.com/reimon08/ticket-lifecycle)
- [osTicket: Post-Installation Configuration](https://github.com/reimon08/osTicket-post-install-config)


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Before we start the project</h2>

<p>DELETE the Maintenance Department (not archive). For some reason, all the tickets keep getting routed there.</p>

https://github.com/user-attachments/assets/2196f575-a166-494e-96d7-f19aa2e41f1e

<p>CHANGE role for John Doe to "expanded access" so that he can view and modify the tickets.</p>

https://github.com/user-attachments/assets/6d1c9be1-01ee-4d41-ab4a-064154cbe2b1





<h2>Example 1</h2>

<h4>Intake</h4>

<p>So, from the end users we set up earlier during the post-installation, we’re gonna create a ticket as Karen. The issue will be that the online banking system is down.</p>

<img width="900" alt="Screenshot 2025-06-23 at 9 25 32 AM" src="https://github.com/user-attachments/assets/b0b6a001-d587-4eb6-a2e8-dd745d4cd9a6" />

<img width="900" alt="Screenshot 2025-06-27 at 11 02 53 AM" src="https://github.com/user-attachments/assets/59c13929-0251-49a5-8847-04a281a36988" />

<h4>Assignment and Communication | Working the Issue | Resolution</h4>

<p>Now we’re gonna log in as John and check out the ticket’s properties.</p>

<p>If you're prompted to change the password, just go ahead and do it, then save it.</p>

<img width="1062" alt="Screenshot 2025-06-27 at 11 29 01 AM" src="https://github.com/user-attachments/assets/c77a555d-d7ab-4b94-a3a4-1046ef823490" />

<h4>Once I’m logged in as John, I’ll check out the ticket, figure out how severe the issue is, and then route it to the right team.</h4>

<p>Since the ticket is banking-related, I’ll assign it to the Online Banking team. I’m also updating the SLA plan to Sev-A since this has a big impact on the business. I changed the help topic to 'Business Critical Outage' and added some notes to help the Online Banking team handle it better.</p>


https://github.com/user-attachments/assets/2df80953-ef8a-41bc-ac97-78330cc6ff24

<p>Alright, now we’re gonna log in as Jane since she’s part of the Online Banking team. And we will work on the ticket from there.</p>

<p>The problem here is that Karen was notified by her employees that the online banking portal isn't working, and it was fixed by Jane by rolling back the updates for now until it is fixed.</p>


https://github.com/user-attachments/assets/65ba132d-1e9c-46e2-8de9-3f5de9d406f8

<h2>Example 2</h2>

<h4>Intake</h4>

<p>As an end-user, we're gonna create a new ticket. This issue now is about Adobe software.</p>


<img width="900" alt="Screenshot 2025-06-28 at 6 55 56 AM" src="https://github.com/user-attachments/assets/e7d0190f-0dcd-482a-a98f-c56da79f109e" />

<p>We’re gonna log back in as John and start working on the ticket from there.</p>

<p>The story here is that only a few people can’t use their Adobe software. Since it’s just a small group, I classified the ticket as Sev-C because it has less impact.</p>

<p>And I will be assigning this to myself (John Doe).</p>


https://github.com/user-attachments/assets/62035a77-e6ef-482e-8551-e3beae88aac4

<p>So the story here is that two people can’t use their Adobe Reader, and they said they’ll call back after lunch.</p>

<p>They finally did the restart, and it worked, so I’m closing the ticket.</p>


https://github.com/user-attachments/assets/05fc4f73-a2d8-4e55-b103-da5db16a9183

<h2>That wraps up our project!</h2>

<p>We’ve successfully gone through the entire osTicket lab — from installation, to post-install setup, all the way through the full life cycle of a Help Desk ticket.</p>

<p>Since we’re done, make sure to stop the VM so you’re not burning money while it’s idle. If you’re totally finished with the lab, feel free to delete the entire resource group to avoid getting charged for storage.</p>

<h4>Thanks for your time and I’m looking forward to doing more labs with you all in the future!</h4>






















