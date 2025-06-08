# implementing-cloud-resources
<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" alt="Microsoft Azure Logo"/>
</p>

<h1>Deploying Resource Groups, Virtual Machines, and Virtual Networks</h1>
This walkthrough covers the setup of basic cloud components in the Azure environment.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure

<h2>Operating System Used </h2>

- Windows 10 (21H2)

<h2>Deployment of Services</h2>

- Create an Azure account and subscription
- Create a resource group
- Create a virtual machine
- Create a virtual network

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/eb161306-c1b7-403e-b076-7533e054645e"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>To create a resource group in Microsoft Azure, sign in to the Azure Portal (or create an account), go to Resource groups, and click "+ Create". Choose your subscription, name the group, select a region, and click "Review + Create" to finish. This sets up a container to organize and manage related cloud resources like VMs and networks. This example demonstrates a resource group designed to support the Active Directory environment, including its virtual machines and networks.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/e75f248e-becc-4454-b7d8-b1bbd9cea6e5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating your resource group in Azure, go to Virtual machines and click "+ Create" > Azure virtual machine. Select the resource group you made, then enter details like the VM name, region, OS image, size, and admin credentials. Finish by reviewing your settings and clicking "Create" to deploy the virtual machine into that group.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/16a17aad-7cd2-48ce-8b51-07202f3e7427" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once your virtual machine is set up, head to Virtual networks in the Azure Portal and select "+ Create". Choose the same resource group and region as your VM, give the network a name, and configure the address space and subnet. Then click "Review + Create" followed by "Create" to launch the virtual network for your VM to connect through.
</p>
<br />
