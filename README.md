<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

![Screenshot 2025-02-13 010602](https://github.com/user-attachments/assets/209871cf-0fe2-4acd-88b5-81caa90205d6)
![Screenshot 2025-02-13 010635](https://github.com/user-attachments/assets/bc8fcbaa-0a3e-4cfa-9273-fa7c41471606)
![Screenshot 2025-02-13 011042](https://github.com/user-attachments/assets/ab66a943-4c82-44e2-b29d-be8b00eb4f71)
![Screenshot 2025-02-13 011145](https://github.com/user-attachments/assets/46dfe013-4a18-4c91-b8f8-4ce5f8190ae3)
![Screenshot 2025-02-13 011154](https://github.com/user-attachments/assets/398a4ea2-4828-4c1c-9456-0cd633340220)
![Screenshot 2025-02-13 011208](https://github.com/user-attachments/assets/90f8516a-c6d0-4996-9788-1e329d9558d4)
![Screenshot 2025-02-13 011237](https://github.com/user-attachments/assets/1b2cbcdb-dbb8-4042-bc5b-066661f912a3)

<p>Configure Roles (for grouping premissions)</p>
<p>Admin panel --> Agents --> Roles</p>
<p><li>Supreme Admin</li></p>
<br />

![Screenshot 2025-02-13 012313](https://github.com/user-attachments/assets/76ec5345-85cc-4f05-81ce-0b02f0d98406)
![Screenshot 2025-02-13 012551](https://github.com/user-attachments/assets/449d9987-8c90-4eb3-9b72-afa967eb1ec0)
![Screenshot 2025-02-13 012634](https://github.com/user-attachments/assets/d820190a-438b-4abf-ad54-df7ac808785e)

<p>Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)</p>
<p>Admin Panel --> Agents --> Roles</p>
<p><li>SysAdmins</li></p>
<br />

![Screenshot 2025-02-13 013339](https://github.com/user-attachments/assets/821fd4b5-a836-4f03-bfca-565dd5c76ce7)
![Screenshot 2025-02-13 013410](https://github.com/user-attachments/assets/111ce19a-ff82-4055-9411-4b526b813e87)

<p>Configure Teams</p>
<p>Admin Panel --> Agents --> Teams (Pull Agents from different Departments)</p>
<p><li>Online Banking</li></p>
<br />

![Screenshot 2025-02-13 013922](https://github.com/user-attachments/assets/10f23e58-5126-4bd6-ae90-8e0dc2492465)

<p>Allow anyone to create tickets</p>
<p>Admin Panel --> Settings --> User Settings (UNCHECK: unregistered users can create tickets)</p>
<p><li>Registration Required: Require registration and login to create tickets</li></p>
<br />

![Screenshot 2025-02-13 014717](https://github.com/user-attachments/assets/a6638cdc-87c6-495c-b5af-77db0a2e1ed3)
![Screenshot 2025-02-13 014941](https://github.com/user-attachments/assets/28ff2958-fd15-4300-ab6f-f5a8d54a3e61)
![Screenshot 2025-02-13 014953](https://github.com/user-attachments/assets/d9e69110-e422-4cc6-999a-e7f5cdfb4ffb)
![Screenshot 2025-02-13 015002](https://github.com/user-attachments/assets/7074fb5e-98d6-4e38-b089-b52b91c41c8a)

<p>Configure Agents (workers)</p>
<p>Admin Panel --> Agents --> Add New</p>
<p><li>Jane (Dept: SysAdmins)</li></p>

![Screenshot 2025-02-13 015535](https://github.com/user-attachments/assets/15bc79fb-0e86-4b65-8ee5-6a47dd3d07e3)
![Screenshot 2025-02-13 015545](https://github.com/user-attachments/assets/a2c32132-bcd8-49dc-a1dc-54b3346d931d)
![Screenshot 2025-02-13 015558](https://github.com/user-attachments/assets/cfa8b1ba-c715-4483-859d-d9a333ea0a5e)

<p><li>John (Dept: Support)</li></p>
<br />

![Screenshot 2025-02-13 020452](https://github.com/user-attachments/assets/80ea3b2e-6f84-4f70-8bd4-1a1333e11666)
![Screenshot 2025-02-13 020552](https://github.com/user-attachments/assets/8232bbc0-8399-4a01-96c6-d65d360d7902)
![Screenshot 2025-02-13 020804](https://github.com/user-attachments/assets/d66896cf-c335-4025-9459-e4fb30835654)

<p>Configure Users (Customers)</p>
<p>Agent Panel --> Users --> Add New</p>
<p><li>Karen</li></p>
<br />

![Screenshot 2025-02-13 021405](https://github.com/user-attachments/assets/ca95bead-b272-4bd9-bafc-19ee42441a94)
![Screenshot 2025-02-13 021634](https://github.com/user-attachments/assets/7559367f-021b-4912-9fe5-4bbc8b9d6e48)
![Screenshot 2025-02-13 021658](https://github.com/user-attachments/assets/c9922ee0-fc34-4dae-861c-763fcd3d356e)
![Screenshot 2025-02-13 021732](https://github.com/user-attachments/assets/710f9482-3381-438b-b625-bf51370eb0d6)
![Screenshot 2025-02-13 021750](https://github.com/user-attachments/assets/55aaad6d-56a4-413e-8af0-5a35dd5f89ac)


<p>Configure SLA</p>
<p>Admin Panel --> Manage --> SLA</p>
<p><li>Sev-A (Grace Period: 1 hour, Schedule: 24/7)</li></p>
<p><li>Sev-B (Grace Period: 4 hour, Schedule: 24/7)</li></p>
<p><li>Sev-C (Grace Period: 8 hour, Schedule: 24/7 [business hours])</li></p>
<br />

![Screenshot 2025-02-13 022225](https://github.com/user-attachments/assets/de622e7e-bf86-4a18-ab16-637624f266f3)
![Screenshot 2025-02-13 022305](https://github.com/user-attachments/assets/88e7a08b-558c-449d-ba62-3499c442bb27)
![Screenshot 2025-02-13 022345](https://github.com/user-attachments/assets/9ed828cf-2cc8-426c-9253-b9efcf4c7b46)
![Screenshot 2025-02-13 022410](https://github.com/user-attachments/assets/e53f713b-6ed6-43db-a68d-479242247b65)
![Screenshot 2025-02-13 022435](https://github.com/user-attachments/assets/06eff391-859f-43aa-a516-605673469e65)
![Screenshot 2025-02-13 022459](https://github.com/user-attachments/assets/1ef32037-4f8f-49ed-a3cf-7151f3b83fba)
![Screenshot 2025-02-13 022513](https://github.com/user-attachments/assets/b682a223-4786-419c-b5dd-6d4bea14adac)


<p>Configure Help Topics (for when users create a ticket</p>
<p>Admin Panel --> Manage --> Help Topics</p>
<p><li>Business Critical Outage</li></p>
<p><li>Personal Computer Issues</li></p>
<p><li>Equipment Request</li></p>
<p><li>Password Reset</li></p>
<p><li>Other</li></p>
<br />
