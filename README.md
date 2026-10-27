\# USJP Distributed Network Labs (IIN 3502)



This repository contains practical Cisco Packet Tracer labs completed as part of my BICT Networking specialized degree at the Faculty of Technology, University of Sri Jayewardenepura. 



\---



\## 🔬 Lab Overviews \& Implementation Details



\### Lab 01: LAN Design \& Hierarchical Network Models

\- \*\*Objective:\*\* Build a two-tier hierarchical campus LAN model (Access, Distribution, and Core/Edge layers) and verify basic connectivity\[cite: 15].

\- \*\*Topology \& Results:\*\*

!\[LAN Topology](./ICT23810\_LAB01/Topology.png)

!\[LAN Testing](./ICT23810\_LAB01/Simulation%20mode%20path.png)



\- \*\*Key Tasks:\*\* 

&#x20; \* Configured Access layer switches (`Switch-2960`) and a Layer 3 Distribution switch (`Switch-3560`)\[cite: 16].

&#x20; \* Established basic device identification, hostnames, passwords, and security banners\[cite: 17].

&#x20; \* Verified end-to-end Layer 2/3 connectivity using ping tests and inspected packet paths using Packet Tracer Simulation Mode\[cite: 18].



\### Lab 02: VLANs, Trunking \& Basic Routing

\- \*\*Objective:\*\* Implement logical network segmentation using VLANs and configure inter-VLAN routing across multiple sites\[cite: 20].

\- \*\*Topology \& Results:\*\*

!\[Trunking \& VLAN Topology](./ICT23810\_LAB02/Topology.png)

!\[Trunking \& VLAN Testing](./ICT23810\_LAB02/show%20vtp%20status.png)

!\[Trunking \& VLAN Testing](./ICT23810\_LAB02/pingServer1-PC3.png)



\- \*\*Key Tasks:\*\*

&#x20; \* Created multiple VLANs (Management, Sales, HR) and assigned member ports\[cite: 20, 21].

&#x20; \* Configured 802.1Q trunk lines between switches and routers\[cite: 20].

&#x20; \* Implemented \*\*Router-on-a-Stick (ROAS)\*\* using subinterfaces and configured static routing between branches\[cite: 21].



\### Lab 03: VTP (VLAN Trunking Protocol) \& Advanced Inter-VLAN Routing

\- \*\*Objective:\*\* Automate VLAN database management across a multi-floor enterprise network using VTP and centralized routing\[cite: 24].

\- \*\*Topology \& Results:\*\*

!\[VTP \& VLAN Topology](./ICT23810\_LAB03/Topology.png)

!\[VTP \& VLAN Testing](./ICT23810\_LAB03/Ping%20from%20PC0-PC1.png)



\- \*\*Key Tasks:\*\*

&#x20; \* Configured a centralized \*\*VTP Server\*\*, \*\*VTP Clients\*\*, and a \*\*VTP Transparent\*\* switch to safely forward or isolate database updates\[cite: 24].

&#x20; \* Deployed IEEE 802.1Q trunking across interconnected switches\[cite: 24].

&#x20; \* Configured Router-on-a-Stick subinterfaces with dot1Q encapsulation to act as default gateways for departments (Sales, Marketing, IT Support)\[cite: 23, 24].



\### Lab 04: Spanning Tree Protocol (STP) \& Redundant Topologies

\- \*\*Objective:\*\* Prevent Layer 2 switching loops in a redundant triangle switch topology using the Spanning Tree Protocol\[cite: 11].

\- \*\*Topology \& Results:\*\*

!\[STP Topology](./ICT23810\_LAB04/Screenshots/LinkFailureTest.png)

!\[STP Testing](./ICT23810\_LAB04/Screenshots/Screenshot%202026-10-23%20201846.png)



\- \*\*Key Tasks:\*\*

&#x20; \* Built a redundant multi-layer switch topology and configured trunk links carrying multiple VLANs\[cite: 12, 13].

&#x20; \* Investigated default STP behavior (identifying Root Ports, Designated Ports, and Alternate/Blocking Ports)\[cite: 13].

&#x20; \* Manually manipulated Bridge Priorities and elected preferred \*\*Root Bridges\*\* for VLANs using PVST+\[cite: 13].

&#x20; \* Tested link failure scenarios to observe automatic topology recovery and convergence\[cite: 13].



\---



\## 🧰 Tools \& Technologies Used

\- \*\*Cisco Packet Tracer\*\*

\- \*\*Protocols:\*\* STP, VTP, 802.1Q Trunking, OSPF/Static Routing, ICMP, TCP/IP

\- \*\*Hardware Models:\*\* Cisco 3560 Multilayer Switches, 2960 Access Switches, 4321/1941 Routers

