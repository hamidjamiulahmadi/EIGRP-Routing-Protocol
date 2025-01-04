<h1>EIGRP Routing Protocol</h1>

<h2>Goal</h2>
<br />In this lab, I will configure the Enhanced Interior Gateway Routing Protocol (EIGRP) to facilitate connectivity between the Frankfurt customer branch and the Berlin sales branch. Additionally, I will incorporate two Internet Service Providers (ISPs) into the network architecture, ensuring that in the event of a connection loss with ISP1, traffic will seamlessly reroute through ISP2 for redundancy. To achieve this objective, I will utilize a total of five Cisco routers, two switches, two personal computers, and two laptops. The initial phase will involve configuring each router with its designated interfaces, followed by the assignment of IP addresses to the PCs and laptops. Subsequently, I will implement the EIGRP protocol on each router, explicitly defining the networks associated with each interface. Finally, I will conduct rigorous testing to confirm the optimal functionality of the entire configuration.. 
<br />


<h2>Environments Used </h2>

- <b>Packet Tracer</b> 
- <b>Windows 11</b>

<h2>Lab walk-through:</h2>
Step Nr.1: The initial step involves creating a network diagram to provide a clearer understanding of the process and illustrate the methodology to be employed.
<p align="center">
Step Nr.1 : Network Diagram: <br/>
<img src="https://i.imgur.com/SHFm9Ml.png" height="80%" width="80%" alt="Lab Steps Nr.1"/>
<br />
Step Nr.2: Subsequently, I will allocate IP addresses to each interface of all routers, ranging from Router 1 to Router 5, in accordance with the specifications outlined in the network diagram.
<p align="center">
Step Nr.2 : allocate IP addresses to each interface of all routers : <br/>
<img src="https://i.imgur.com/gVlT4w2.png" height="80%" width="80%" alt="Lab Steps Nr.2"/>
<img src="https://i.imgur.com/EpYsoQh.png" height="80%" width="80%" alt="Lab Steps Nr.2"/>
<img src="https://i.imgur.com/5deWxB7.png" height="80%" width="80%" alt="Lab Steps Nr.2"/>
<img src="https://i.imgur.com/9Mw5SVt.png" height="80%" width="80%" alt="Lab Steps Nr.2"/>
<img src="https://i.imgur.com/bMheijf.png" height="80%" width="80%" alt="Lab Steps Nr.2"/>
<br />
Step Nr.3: Next, I will assign the appropriate IP addresses to each PC and laptop in accordance with their respective networks.
<p align="center">
Step Nr.3 : assign IP addresses: <br/>
<img src="https://i.imgur.com/gomXkAW.png" height="80%" width="80%" alt="Lab Steps Nr.3"/>
<img src="https://i.imgur.com/fIM3vdq.png" height="80%" width="80%" alt="Lab Steps Nr.3"/>
<br />
Step Nr.4: I will now begin the configuration of the EIGRP protocol for each router, specifying the networks for each interface to ensure proper network connectivity.
<p align="center">
Step Nr.4 : configuration of the EIGRP: <br/>
<img src="https://i.imgur.com/Ron8v6A.png" height="80%" width="80%" alt="Lab Steps Nr.4"/>
<img src="https://i.imgur.com/3kyjXIP.png" height="80%" width="80%" alt="Lab Steps Nr.4"/>
<img src="https://i.imgur.com/Asm269X.png" height="80%" width="80%" alt="Lab Steps Nr.4"/>
<img src="https://i.imgur.com/7Z0GVbM.png" height="80%" width="80%" alt="Lab Steps Nr.4"/>
<img src="https://i.imgur.com/T8l6Szf.png" height="80%" width="80%" alt="Lab Steps Nr.4"/>
<br />
Step Nr.5: Following the configuration of EIGRP, I will now initiate a ping from the Frankfurt customer branch to the Berlin sales branch, as well as in the reverse direction, to verify that the computers are able to communicate with each other and ensure network connectivity.
<p align="center">
Step Nr.5 : ping of communication : <br/>
<img src="https://i.imgur.com/bapyRfa.png" height="80%" width="80%" alt="Lab Steps Nr.5"/>
<img src="https://i.imgur.com/VirWWQI.png" height="80%" width="80%" alt="Lab Steps Nr.5"/>
<br />
Step Nr.6: As demonstrated previously, the computers can effectively communicate with one another. I will now utilize the Tracert command to ascertain the path to a specified destination by sending Internet Control Message Protocol (ICMP) echo packets. This will provide an overview of the network, and as you can observe, the lab has been successfully completed.
<p align="center">
Step Nr.6 : Lab Accomplishment : <br/>
<img src="https://i.imgur.com/UQnhuLd.png" height="80%" width="80%" alt="Lab Steps Nr.6"/>
<img src="https://i.imgur.com/xEuuOqC.png" height="80%" width="80%" alt="Lab Steps Nr.6"/>
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
