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

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>Sev-A (1 hour, 24/7) [entire mobile/online banking system is down] -> SysAdmins</h3>

![Screenshot 2024-03-13 at 3 58 59 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/dc4600fb-94f7-4f34-b29a-2970ca7135ad)

<h4>Rick creates a ticket</h4>
<p>
  To create a ticket as the user Rick Sanchez in osTicket, Rick would first need to access the client portal, typically through a web interface provided by the organization using osTicket. Upon reaching the portal, he would select the option to "Open a New Ticket" or a similarly labeled action. In the ticket submission form, Rick would enter his details—assuming his user profile is already created in the system, he might need to log in or his information could be auto-filled. He would then describe the issue or request in the provided fields, specifying the subject and detailed description, and select the relevant help topic or department that best matches his needs. If necessary, Rick could also attach any files that support his ticket. After reviewing his submission for accuracy, he would submit the ticket, which then gets logged into the osTicket system, generating a unique ticket ID for tracking and follow-up, and triggering any configured notifications or workflows related to new ticket submissions.
</p>
<br/>

![Screenshot 2024-03-13 at 4 02 56 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/f5c59b42-db70-4164-9289-dcbd624766e2)

<h4>Jane create ticket priority </h4>
<p>
  As Jane, the admin in osTicket, adjusting ticket priority involves logging into the administrative backend with her credentials. Once logged in, she would navigate to the "Tickets" section and locate the specific ticket whose priority needs adjustment. Upon opening the ticket's detailed view, Jane would look for the "Priority" field, which is typically part of the ticket's basic information or settings. This field usually contains a dropdown menu from which she can select a new priority level for the ticket—such as "Low," "Normal," "High," or any custom priorities that have been defined in the osTicket system settings. After selecting the desired priority level, Jane would save the changes, effectively updating the ticket's priority. This action might trigger notifications to the relevant parties, such as the ticket owner and assigned agents, to inform them of the change in priority, depending on the notification settings configured within osTicket. This process helps in ensuring that tickets are handled according to their urgency and impact, allowing the support team to better manage their workload and respond effectively to user needs.
</p>
<br/>


![Screenshot 2024-03-13 at 4 03 34 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/2e8388c3-a1dc-42d0-911a-34ccd0ab57fb)

<h4>Jane assigns ticket to self</h4>
<p>
  Jane would find the "Assign to" option, which could be a button or a dropdown menu within the ticket's detailed view. She would select or type her own name in this field, thereby reassigning the ticket from its current assignee or status to herself. After selecting her name, Jane would confirm the assignment by saving the changes or clicking an "Assign" button, depending on the specific interface design of her osTicket system. This action transfers the responsibility of the ticket to Jane, allowing her to manage its resolution directly. The system may also notify Rick and any other relevant parties about this change in ticket assignment, ensuring transparency and communication within the ticket's lifecycle.
</p>
<br/>


![Screenshot 2024-03-13 at 4 04 05 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/24423705-55e8-42d1-95ec-0c946088035a)

<h4>Jane updates SLA</h4>
<p>
  Jane can update the Service Level Agreement (SLA) to "Sev-A" for a specific ticket or as a default for certain types of tickets by accessing the administrative panel. If updating SLA for an individual ticket, she would navigate to the "Tickets" section, locate the ticket in question, and open its detailed view. Within the ticket's details, Jane would look for the "SLA Plan" field. Here, she can select "Sev-A" from a dropdown list of predefined SLA plans. After selecting "Sev-A" for the ticket, she would save the changes, thereby updating the ticket's SLA. This adjustment might trigger notifications to the relevant parties and will dictate the priority and response requirements for the ticket moving forward, ensuring it's handled according to the "Sev-A" specifications.
</p>
<br/>


![Screenshot 2024-03-13 at 4 05 12 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/7d0d0bf9-eee0-4c4e-8319-8df78dcf5bd3)

<h4>Jane assigns department</h4>
<p>
  Within the ticket details, Jane would look for the option to edit or change the department. She would then select the desired department from a dropdown list or through a search function within this option. Upon choosing the appropriate department, Jane would save the changes, effectively reassigning the ticket. This action may trigger notifications to the relevant staff members within the new department, alerting them of the newly assigned ticket and ensuring that it is addressed by the appropriate team, in line with the organization's workflow and service level agreements.
</p>
<br/>


![Screenshot 2024-03-13 at 4 06 27 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/039c68c8-8969-4d90-870e-e95f115c2a16)

<h4>Jane post reply to ticket</h4>
<p>
  Jane can post a reply to a ticket by logging into the administrative or agent interface, depending on her role, and navigating to the "Tickets" section. Once she locates the specific ticket she wishes to respond to, she can open it to view its details. Within the ticket view, there is typically a "Post Reply" button or a reply field where Jane can enter her message to the ticket requester or any other participant in the ticket conversation. After composing her response, she can use any available formatting tools to structure her message effectively and, if necessary, attach files that may help in resolving the ticket or providing additional information. Before posting her reply, Jane has the option to preview it to ensure accuracy and clarity. Once satisfied, she can submit her reply, which will then be recorded in the ticket's history and, depending on the osTicket configuration, sent as an email notification to the ticket requester and any other relevant parties. This process enables Jane to maintain clear and effective communication with users, providing them with the assistance or information they need.
</p>
<br/>


![Screenshot 2024-03-13 at 4 08 43 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/b72ad186-7682-4e48-afc0-48b8f1a69e1c)

<h4>Assigned agent fixes issue and resolves ticket</h4>
<p>
  To resolve a ticket in osTicket, Jane, acting in her administrative or agent capacity, would first access the ticket in question through the osTicket administrative dashboard. She would navigate to the "Tickets" section and select the ticket she intends to resolve, opening its detailed view. Within this view, Jane would find options or actions related to ticket status, such as a "Close Ticket" or "Resolve Ticket" button, which might be located near the top of the page or within a drop-down menu of actions. Before changing the ticket's status to resolved, Jane could post a final reply or solution within the ticket thread, ensuring that the requester and any other participants have a clear understanding of the resolution. Upon closing or marking the ticket as resolved, Jane might have the option to categorize the resolution (e.g., fixed, user error, no issue) and add any closing notes for internal documentation. This action updates the ticket's status in the system, typically triggering notifications to inform the ticket requester and any other relevant parties that the issue has been addressed. Resolving a ticket effectively closes the loop on that particular issue, documenting the outcome and solution within osTicket for future reference.
</p>
<br/>


<h3>Sev-B (4 hours, 24/7) [accounting department needs adobe upgrade, broken]</h3>

![Screenshot 2024-03-13 at 4 16 09 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/f95b0e12-138a-48cf-8b1e-fea8bf7b5b5c)

<h4>Rick creates a ticket</h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 17 38 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/4a46a5b4-572e-4a64-9399-5e814f3d4cd5)

<h4>Jane create ticket priority </h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 19 52 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/11e5f722-98b0-4179-9a0a-06c4d96976a9)

<h4>Jane assigns ticket to John</h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 20 31 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/d1f18d43-03df-4ca2-9526-981dd844adb9)

<h4>Jane updates SLA </h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 21 02 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/b0bea81b-a5d8-4a47-8899-60306b4d2b63)

<h4>Jane assigns department</h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 22 43 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/0edee1ad-f86e-41ec-9ac2-ff02245f6316)

<h4>Jane post reply to ticket</h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 30 14 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/98fe9b07-7e31-4621-96d9-f6039d7f12ca)

<h4>Assigned agent fixes issue and resolves ticket</h4>
<p>
  
</p>
<br/>


<h3>Sev-C (2 hours, business hours) [CFO’s laptop seems a bit slow]</h3>

![Screenshot 2024-03-13 at 4 35 59 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/ee1a103b-c9eb-4328-be15-74d489422cda)

<h4>Morty creates a ticket</h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 36 34 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/ffabab3c-fca3-4f1a-9d21-1cbd031d5e35)

<h4>Jane create ticket priority </h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 37 00 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/e1f232dc-af1d-4397-be20-f9cb0a4ff844)

<h4>Jane assigns ticket to self</h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 37 27 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/1bc37a22-72c2-46db-967b-51c8db4493e8)

<h4>Jane updates SLA </h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 37 53 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/a1c9eed9-6f7c-41fb-860d-f05c82393be5)

<h4>Jane assigns department</h4>
<p>
  
</p>
<br/>


![Screenshot 2024-03-13 at 4 38 58 PM](https://github.com/ory-it/ticket-lifecycle/assets/67742620/e751f87a-5ef3-46bc-bfc1-61197726c4bf)

<h4>Jane post reply to ticket and closes ticket</h4>
<p>
  
</p>
<br/>

