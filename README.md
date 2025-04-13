<h1>AWS AMI Creation with Packer and Ansible</h1>


<h2>Description</h2>
This project automates the creation of a custom Amazon Machine Image (AMI) using Packer and Ansible. It provisions an EC2 instance, applies updates, installs required software, and configures the system with Ansible playbooks. The result is a reusable AMI for consistent and secure deployments.
<br />


<h2>Utilities Used</h2>

- Packer
- Ansible
- Amazon EC2
- AWS CLI


<h2>Project Walk-through</h2>

<p align="center">
Set Up Packer, Ansible, and AWS CLI <br />
<img src="https://i.imgur.com/clwOB8s.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Packer Configuration <br/>
<img src="https://i.imgur.com/Zst54BN.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Define Provisioning with Ansible <br/>
<img src="https://i.imgur.com/30ZgySm.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run the Packer Build <br/>
<img src="https://i.imgur.com/7nFp9hR.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Newly Created AMI in the AWS Management Console.
<br/>
<img src="https://i.imgur.com/jtwNhDR.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
