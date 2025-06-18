# CCNA in the world of the Lord of the Rings
## Network scheme
Hobbits create computer network in the Shire. Create a table that contains the network address, host ranges, and broadcast address and subnet mask. Create a network diagram with subnetting. The initial LAN is 8.31.0.0/16  and the initial WAN is 152.42.168.0/20.  
  
Required number of devices in networks:  
![alt text](./assets/network1.png)  
Network diagram with division into subnets:  
![alt text](./assets/network2.png)  
A developed network 8.31.0.0/16 and 152.42.168.0/12:  
![alt text](./assets/network3.png)  
## RIP_v2
Make diagram of the networks below.  
![alt text](./assets/network4.png)  
After assigning IP addresses to router interfaces and computers, start the RIPv2 protocol.  
![alt text](./assets/router1.png)  
![alt text](./assets/router2.png)  
![alt text](./assets/router3.png)  
![alt text](./assets/router4.png)  
![alt text](./assets/router5.png)  
Checking the routing table of router R1.  
![alt text](./assets/iproute.png)  
Test the connection between PC1 and PC2.  
![alt text](./assets/test.png)  
## VLAN
Make the following network diagram. Assign appropriate IP addresses to workstations.  
![alt text](./assets/vlan1.png)  
Create VLANs in switches and assign them appropriate interfaces. Start access mode on interfaces.  
![alt text](./assets/vlan2.png)  
Use the show vlan brief command to check if the interfaces are assigned to the indicated VLANs. Then configure the Sw2 switch similarly.  
![alt text](./assets/vlan3.png)  
Create a trunk connection between switches.  
![alt text](./assets/vlan4.png)  
Test the connection between workstations PC1 and PC5.  
![alt text](./assets/vlan5.png)  
## VTP
![alt text](./assets/VTP.png)  
## Inter-VLAN Routing - classic method
In the classic method, the router requires configuration of interfaces, each of which belongs to one VLAN.  
![alt text](./assets/inter-vlan-routing-classic-0.png)  
Creating VLAN 10, VLAN 20, VLAN 30 and naming them.  
![alt text](./assets/inter-vlan-routing-classic-1.png)  
Assigning interfaces to VLANs and configuring interfaces to work in access mode.  
![alt text](./assets/inter-vlan-routing-classic-2.png)  
![alt text](./assets/inter-vlan-routing-classic-3.png)  
Checking if interfaces are in the correct VLANs.  
![alt text](./assets/inter-vlan-routing-classic-4.png)  
Assigning IP interests to router interfaces and starting them.  
![alt text](./assets/inter-vlan-routing-classic-5.png)  
Displaying a list of interfaces on the router.  
![alt text](./assets/inter-vlan-routing-classic-6.png)  
Checking the connection between workstation PC1 and PC2 and PC3. 
![alt text](./assets/inter-vlan-routing-classic-7.png)  
## Inter-VLAN Routing - router on a stick
In the router on a stick method, only one wire is used for routing between VLANs in the router.  
![alt text](./assets/inter-vlan-routing-stick-0.png)  
Using subinterface-based functionality. After creating a subinterface, indicate encapsulation and provide a VLAN id.  
![alt text](./assets/inter-vlan-routing-stick-1.png)  
Enable the interface.  
![alt text](./assets/inter-vlan-routing-stick-2.png)  
Displaying a list of interfaces on the router.  
![alt text](./assets/inter-vlan-routing-stick-3.png)  
After creating VLAN 10, VLAN 20, VLAN 30 on the switch and giving them names, assign interfaces to VLANs and configure the interfaces to work in access mode.  
![alt text](./assets/inter-vlan-routing-stick-4.png)  
Checking the connection between workstation PC1 and PC2 and PC3.  
![alt text](./assets/inter-vlan-routing-stick-5.png)  
## Inter-VLAN Routing - L3 switch
Routing between VLANs using a Layer 3 switch performing routing within a single local area network.  
![alt text](./assets//inter-vlan-routing-L3-0.png)  
Starting routing on the L3 switch. Creating VLAN 10, VLAN 20, VLAN 30. 
Assigning interfaces to VLANs and configuring interfaces to work in access mode. Assigning IP addresses to interfaces and starting them.  
![alt text](./assets//inter-vlan-routing-L3-1.png)  
Displaying the routing table.  
![alt text](./assets//inter-vlan-routing-L3-2.png)  
Displaying the routing table.  
![alt text](./assets//inter-vlan-routing-L3-3.png)  
