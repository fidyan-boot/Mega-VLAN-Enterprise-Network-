# Mega VLAN Enterprise Network with Inter-VLAN Routing

## 📌 Project Overview
This project demonstrates the design and implementation of a Mega VLAN enterprise network using Cisco Packet Tracer. Multiple departments are segmented into different VLANs with inter-VLAN communication enabled through Router-on-a-Stick.

## 🛠 Technologies Used
- VLAN & Trunking (802.1Q)
- Inter-VLAN Routing
- DHCP Configuration
- Access Control Lists (ACL)
- Cisco Packet Tracer

## 🗂 VLAN & IP Addressing Scheme
| VLAN | Department | Network | Gateway |
|-----|-----------|---------|---------|
| 10 | Admin | 192.168.10.0/24 | 192.168.10.1 |
| 20 | HR | 192.168.20.0/24 | 192.168.20.1 |
| 30 | IT | 192.168.30.0/24 | 192.168.30.1 |
| 40 | Sales | 192.168.40.0/24 | 192.168.40.1 |
| 50 | Finance | 192.168.50.0/24 | 192.168.50.1 |
| 99 | Guest | 192.168.99.0/24 | 192.168.99.1 |

## 🔧 Key Configurations
- VLAN creation and port assignment on switch
- Trunk configuration between router and switch
- Router sub-interfaces for each VLAN
- DHCP pools configured on router
- ACL applied to restrict Guest VLAN access

## 🧪 Verification & Testing
- Successful inter-VLAN ping between departments
- DHCP assigns IP addresses correctly
- Guest VLAN traffic blocked from internal networks

## 📸 Screenshots
Refer to the screenshots folder for verification outputs.

## 📎 Tools
- Cisco Packet Tracer

👤 Author
Name:FIDYAN JAMBHARKAR
