<h1>DNS</h1>

<h2>Description</h2>
This lab will configure a network using DNS. All IP addresses have beeen configured on the router interfaces and servers.
<br />

<h2>Environments Used </h2>

- <b>Packet Tracer</b>

<h2>Lab walk-through:</h2>

<p align="center">
<h4>Lab Topology:</h4>
In this Lab topology the network devices will be configured to communicate with each other using their FQDN(hsot names). <br/>
The lab consists of 3 routers, 2 switches and 1 DNS server. <br/>
<img src="https://i.imgur.com/ahRL7t6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h4>Before DNS is configured:</h4> 
Before DNS is configured the devices can ping each other using their IP addresses, but cannot ping each other suing their FQDN(host names).<br/>
Router 2 can ping every devices using IP adresses, but not hostnames..<br/>
<img src="https://i.imgur.com/jjwHgzw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
<img src="https://i.imgur.com/Duiwtoe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<h4>NS Configuration:</h4>
The DNS Configuration on the DNS Server 
<img src="https://i.imgur.com/JL6G74Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
The DNS Configuration on the routers and switches
<img src="https://i.imgur.com/sPbvim2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />

<h4>After DNS is configured:</h4> 
Router 2 can now ping all other devices using their hostnames.<br/>
<img src="https://i.imgur.com/rE1XQVQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
