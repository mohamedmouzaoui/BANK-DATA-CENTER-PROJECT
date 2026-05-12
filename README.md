# Bank Data Center – Cisco Packet Tracer Lab

This project is a production-style bank data center network built in Cisco Packet Tracer 8.1, designed to simulate how a real enterprise banking infrastructure operates with security, redundancy, segmentation, and dynamic routing.

The topology follows a complete multi-tier architecture that includes ISP connectivity, core routing, firewall security layers, aggregation switches, and access switches supporting multiple VLANs and critical banking services. The lab demonstrates how modern enterprise networks are structured to provide high availability, scalability, and secure communication between internal systems and external networks.

The network contains 21 fully configured devices including Cisco 2911 routers, Layer 3 and Layer 2 switches, ASA firewalls, and multiple server systems such as SOC, SIEM, IDS/IPS, load balancer, and database servers. Technologies implemented in the project include OSPF for internal dynamic routing, BGP for ISP peering, HSRP for gateway redundancy, VLAN segmentation, NAT/PAT, ACL-based security policies, and QoS for traffic prioritization.

The infrastructure is divided into multiple VLANs dedicated to management, servers, databases, internal operations, SOC monitoring, SIEM logging, and storage services. Redundancy is implemented across the core and aggregation layers using HSRP and dual ISP uplinks to ensure continuous connectivity in case of device or link failure.

Security is a major focus of the project. Two ASA firewalls create a protected DMZ architecture, enforce access control policies, filter spoofed traffic, and restrict database access only to authorized networks. Internal security monitoring systems such as IDS, IPS, SOC, and SIEM servers are also integrated into the environment to simulate a realistic cyber defense setup.

This lab is ideal for students, cybersecurity learners, CCNA/CCNP candidates, and network engineers who want hands-on experience with enterprise networking concepts in a realistic banking environment. It can be used for learning, demonstrations, security testing, routing practice, or as a foundation for more advanced network simulations.
