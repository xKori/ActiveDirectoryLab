# Active Directory Lab
Tutorial I used to **set up the homelab**: https://www.youtube.com/watch?v=MHsI8hJmggI

<img width="1748" height="850" alt="image" src="https://github.com/user-attachments/assets/f328ca03-f5ac-439c-b89b-bff3eb4417a5" />
<img width="1748" height="857" alt="image" src="https://github.com/user-attachments/assets/ae4199a9-fb45-4c40-9a93-07cab68f2213" />

<h1>Active Directory Home Lab Setup</h1>
<ul>
  <li>Created Windows Server 2019 Virtual Machine as the Domain Controller</li>
<li>Configured internal (DHCP) + external (Assigned IP) NICs</li>
<li>Installed Active Directory onto Windows Server 2019</li>
<li>Added a new forest</li>
<li>Added an organizational unit (OU) called "_ADMINS_" and created an admin account to practice security hardening best practices</li>
<li>Added remote access server role and routing</li>
<li>Added NAT to remote access server config</li>
<li>Added DHCP role to server</li>
<li>Created windows 10 "client" Virtual Machine</li>
<li>Connected windows 10 "client" VM to the Active Directory domain to verify connection</li>
</ul>

<h2>Active Directory Experience</h2>
<p>After creating the lab I practiced common administrative tasks in Active Directory</p>

<h3>User Account Management</h3>
<ol>
  <li>Adding new user accounts</li>
  <li>Disabling/enabling accounts</li>
  <li>Resetting Passwords</li>
  <li>Unlocking accounts</li>
  <li>Updating user details</li>
</ol>

<h3>Group Management</h3>
<ol>
  <li>Learned about AGDLP nesting methodoloy</li>
  <li>Adding/removing users from groups</li>
  <li>Moving users from groups</li>
  <li>Organizational Units (OUs)</li>
  <li>Safely moving users/computers between OUs</li>
</ol>
