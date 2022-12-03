# Network-Infrastructure-Architecture

For the scenario below, represent in an Infrastructure Architecture diagram all distinct network architecture components and how they integrate with each other. You must clearly mark the boundaries of each component as well as the inbound and outbound flow to the network.

Scenario: A company operates within two campuses, both campuses need access to the public Internet. Show all network architecture components for the two buildings.
The following scenario illustrates the network architecture components for the two campuses.

Campus A:
- Firewall: Establishes a secure boundary between the internal network and the public internet. It inspects all communication traffic to ensure that malicious traffic is not allowed in. 
- Router: Connects the internal network to the external Internet. It is responsible for directing traffic both to and from the Internet.
- Switch: Connects all components of the internal network and allows for communication between them.
- Access Point: Provides wireless access to the internal network. It connects users to the internal network without the need for physical cables.

Campus B:
- Firewall: Establishes a secure boundary between the internal network and the public internet. It inspects all communication traffic to ensure that malicious traffic is not allowed in. 
- Router: Connects the internal network to the external Internet. It is responsible for directing traffic both to and from the Internet.
- Switch: Connects all components of the internal network and allows for communication between them.
- Access Point: Provides wireless access to the internal network. It connects users to the internal network without the need for physical cables.


Problem 2 (Points: 30): Answer the following questions in detail and provide examples:
Illustrate and describe in your own words how will you design a Wireless LAN for the following scenario:
Two story building 300 ft by 300 ft area.
WAP devices with a range of 100 ft diameter.
To design a Wireless LAN for a two story building with a 300 ft by 300 ft area and WAP devices with a range of 100 ft diameter, I would first begin by calculating how many WAPs are needed. I would need to divide the area up into 100 ft diameter circles (the range of the WAPs). This would require a total of 9 WAPs. 

Next, I would need to decide where to place the WAPs. I would need to make sure that the WAPs are placed in such a way that there is no overlap of coverage, and that each WAP is able to provide coverage to the entire area. To do this, I would place the WAPs in the corners and center of each side of the building, and then place one WAP on each floor in the center of the building. This would ensure that there is no overlap in coverage and that each WAP provides coverage to its designated area. 

Finally, I would need to configure the WAPs. This would involve setting up the SSIDs, security settings, and other parameters. I would also need to make sure that each WAP is connected to the same network and that they are able to communicate with each other

Problem 3 (Points: 20): Answer the following questions in detail and provide examples:
How does a layer-2 switch differ from a router?
Answer:
A layer 2 switch is primarily responsible for transporting data on a physical layer and in performing error 
checking on each transmitted and received frame. A layer 2 switch requires MAC 
address of NIC on each network node to transmit data.Routers on the other hand 
allow us the ability to take different networks and pass traffic to one another 
in Layer 3.

Under what circumstances would you want to use a routed backbone?

