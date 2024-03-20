<p align="center">
<img alt="1" src="https://github.com/giovannibriones/ad-user-generation/assets/163789590/e692ac0b-3512-4cc7-b912-7b58b89043ec"/>

</p>

<h1> Active Directory: User Generation </h1>


<p>Welcome to the "Active Directory User Generation" project. In this project, we'll create user accounts using a powershell script to populate our domain for future use in simulated scenarios. </p>

<h2>Prerequisites</h2>

- <a href="https://github.com/giovannibriones/ad-and-azuresetup"> Preliminary Setup for Active Directory and Network Traffic Analysis between Azure VMs </a>
- <a href="https://github.com/giovannibriones/ad-deployment-configuration"> Active Directory Deployment and Configuration </a>

<h2>Key Objectives</h2>

<h4>User Creation</h4>

-  Create a number of users using a power shell script in order to populate our domain

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h1>User Creation</h1>

<h3>&#9312; Run PowerShell script</h3>
<p>First we will be using a Powershell script to generate a number of users for our Active Directory Domain. 
</p>

- Login to DC-01 as jane_admin
- Open PowerShell_ise as an administrator and paste the contents of the <a href="https://github.com/joshmadakor1/AD_PS/blob/master/Generate-Names-Create-Users.ps1"> script </a> and run it. 

<br>

<img width="821" alt="2" src="https://github.com/giovannibriones/ad-user-generation/assets/163789590/f8c6ed02-4961-43c7-a534-d705bbcee117">


<p><strong>The script will generate a number of users with a combination of consonants and vowels so the names might be unusual. </strong> </p>

<p>
</p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Once the script is done running, you can verify in Active Directory that the users have been created.</strong></p>

<img width="562" alt="3" src="https://github.com/giovannibriones/ad-user-generation/assets/163789590/0f28eb98-e9ae-40a6-9d5f-2a020c5bbd1f">


<h3>&#9313; Login as user </h3>

- Now you can try logging in as one of the users to further verify that the script has worked.
- Take note of the default password in the script (Password1)

<img width="335" alt="4" src="https://github.com/giovannibriones/ad-user-generation/assets/163789590/08b77b23-6732-41cf-a6e8-fdb5e80a8a7d">


<h2> In Conclusion </h2>

<p> In summary, the "Active Directory User Generation" project streamlines our user management process. Using a PowerShell script, we efficiently create user accounts, setting the stage for the next projects.</p>









