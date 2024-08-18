College Campus Network Topology
This project details a meticulously designed network topology for a college campus, structured into two distinct blocks: the Main Block and the Branch Block. Each block is equipped with its own set of essential network components to ensure a secure, scalable, and high-performing network environment.

Main Block
ISP Router and Firewall: The Main Block operates with its own ISP router and firewall, providing a dedicated pathway for internet access and external communication. This setup ensures that network traffic is efficiently managed and securely handled.
DMZ and Management Block: The Main Block features a DMZ (Demilitarized Zone) for housing critical servers, adding an extra layer of security by isolating them from the internal network. Additionally, a Management Block is in place to oversee and control all network devices, including wireless LANs, ensuring centralized and streamlined network administration.
Departments: Within the Main Block, the following departments are accommodated: CE (Computer Engineering), ECE (Electronics and Communication Engineering), CSE (Computer Science and Engineering), EEE (Electrical and Electronics Engineering), and AIML (Artificial Intelligence and Machine Learning).
Network Configuration: The network is powered by two multilayer switches to handle extensive traffic loads. Key configurations include LAPC Ethernet channels to enhance link performance, OSPF (Open Shortest Path First) for dynamic routing, and HSRP (Hot Standby Router Protocol) for high availability and failover. The Main Block’s firewall is configured with DHCP (Dynamic Host Configuration Protocol) for automated IP addressing, and IPsec (Internet Protocol Security) is implemented to secure data transmission across the network. Inter-VLAN routing ensures efficient communication between different departmental networks, and STP (Spanning Tree Protocol) is utilized to prevent broadcast storms. Wireless devices are configured to seamlessly integrate with the wired infrastructure, ensuring comprehensive coverage and connectivity.
Branch Block
ISP Router and Firewall: Like the Main Block, the Branch Block is equipped with its own ISP router and firewall, maintaining an independent and secure network environment. This redundancy enhances overall network reliability.
Departments: The Branch Block is home to the Automobile, Data Science, Civil, and Mechanical Engineering departments, each connected to the network for seamless access to resources.
Network Configuration: The Branch Block mirrors the Main Block with two multilayer switches, ensuring efficient traffic handling. The same advanced network configurations—LAPC Ethernet channels, OSPF, HSRP, DHCP-configured firewalls, IPsec, and inter-VLAN routing—are applied here as well. Wireless device configurations and STP ensure robust connectivity and network stability within this block.
This comprehensive network topology is designed to meet the diverse needs of a modern educational institution, providing secure, reliable, and scalable networking solutions that effectively manage both wired and wireless devices across the entire campus.

