<p align="center">
<img src="https://i.imgur.com/7Rue9e4.jpg" alt="VPN Logo"/>
</p>

Hello, my name is Meshach Simotwo and I am a IT Professional. Today I will be showing you the steps to installing and configuring a Virtual Private Network (VPN). This tutorial outlines the prerequisites and installation of making a VPN.<br>

<h1>Virtual Private Network's (VPN)</h1>

- A Virtual Private Network, also known as a VPN, is a platform where you can securely connect two devices on a insecure network such as the Internet. It allows them to send data to each other in an encrypted form.
  - Most likely you will use a VPN to connect to common resources such as from a work connection to home.
- Here below is a quick YouTube video link famous youtuber Techouse! He explains and goes into furthermore detail on why you should use a VPN in different scenarios.
https://youtu.be/hsD5PXyJ93A

<h2>In this tutorial, we will be using ProtonVPN to set up a mock VPN for practice.</h2>

*<h2>Environments and Technologies Used</h2>*
  - Microsoft Azure (Virtual Machines/Compute)
  - ProtonVPN
  - Whatismyipaddress.com
https://account.protonvpn.com/signup?plan=free&language=en

<h2>Steps to making a VPN</h2>

- Create a Resource group in Microsoft Azure
  - If you dont know how to use Azure, I have a repository guide on how to obtain a subscription. 
https://github.com/msimotwo/mszuresubscription

<p align="center">
<img src="https://i.imgur.com/e4y4ryD.png" alt="VPN Logo"/>
</p>

- Within that resource group, create a Windows 10 Virtual Machine in another region.
  - Ex.( Japan, South Africa, etc. Basically somewhere else that is not your locatiion.)

<p align="center">
<img src="https://i.imgur.com/S0Cu0zO.png" alt="VPN Logo"/>
</p>

- Log into the VM with Remote Desktop
  - Use Microsoft Edge and look up "Whatismyipaddress.com" 
  - Your IP Information should reside onto where you located your VM.

<p align="left">
<img src="https://i.imgur.com/EgycVKF.jpg" alt="VPN Logo"/>
</p>

- Now try this and experiment!
  - Using your new IP information, start looking up websites that you would use on a daily basis. Such as Google, YouTube, Instagram, etc. You will see that there will most likely be a difference in how the site looks versus your location's regular site. The URL might even be different. 
  
- Clean and delete Microsoft Azure Resource Groups and VM's.
  - Log out of your VM, and head over to Azure.
    - Make sure to delete all Resource Groups and VM's. Any background activity will lead to a charge on your account $$$. Save that money!

