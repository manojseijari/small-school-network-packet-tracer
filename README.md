<img width="1862" height="611" alt="Screenshot 2026-08-04 104554" src="https://github.com/user-attachments/assets/814e40d9-a002-4264-b4e4-334ca4647099" />
small-school-network-packet-tracer
A Cisco Packet Tracer project simulating a small school network with VLAN segmentation, Router-on-a-Stick, inter-VLAN routing, DHCP, DNS, HTTP, and ACL-based security.

🏫 Network Topology

- 1 × Router
- 1 × Layer 2 Switch
- 1 × Server
- 1 × Network Printer
- 16 × Desktop PCs
- 1 × Laptop

🌐 VLAN Design

VLAN 10 – Administration
Network: 192.168.10.0/24
Default Gateway: 192.168.10.1
Devices: 3 Desktop PCs, 1 Network Printer

VLAN 20 – Teachers
Network: 192.168.20.0/24
Default Gateway: 192.168.20.1
Devices: 3 Desktop PCs, 1 Laptop

VLAN 30 – Computer Lab
Network: 192.168.30.0/24
Default Gateway: 192.168.30.1
Devices: 10 Desktop PCs

VLAN 40 – Server Room
Network: 192.168.40.0/24
Default Gateway: 192.168.40.1
Devices: 1 Server


⚙️ Features Implemented

- VLAN Configuration
- Access Port Configuration
- 802.1Q Trunking
- Router-on-a-Stick
- Inter-VLAN Routing
- DHCP Server Configuration
- DNS Server Configuration
- HTTP Server Configuration
- Network Printer Integration
- Access Control Lists (ACLs)
- Basic Network Troubleshooting
- Static IP on Server and Printer

🔒 Security

- ACLs configured to restrict Computer Lab (VLAN 30) from accessing the Server VLAN (VLAN 40).
- Administration and Teachers VLANs retain access to network resources and services.


🎯 Skills Demonstrated

- Network Design
- VLAN Segmentation
- Layer 2 Switching
- Inter-VLAN Routing
- DHCP Configuration
- DNS Configuration
- HTTP Server Configuration
- Access Control Lists (ACLs)
- Cisco IOS Configuration
- Network Troubleshooting

 Author
Manoj Seijari
