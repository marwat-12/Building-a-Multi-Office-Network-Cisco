# 🏢 Office Management System – Cisco Packet Tracer

### Enterprise Network Design & Router CLI Configuration

## 📌 Project Overview

The **Office Management System** is an enterprise-level network simulation developed using **Cisco Packet Tracer**. The project demonstrates the design and implementation of a multi-office network in which different departments, servers, printers, IP phones, and security systems are interconnected through routers and switches.

The main objective is to establish reliable communication between all departments using proper IP addressing, router configuration, and dynamic routing with RIP Version 2 (RIPv2).

This project also includes router CLI configurations, network topology, device connectivity, and practical network testing.

## 🎯 Project Objectives

- Design a complete multi-office enterprise network.
- Connect multiple departments through routers and switches.
- Implement static IP addressing for network devices.
- Configure routers using Cisco CLI commands.
- Implement RIP Version 2 for dynamic routing.
- Establish communication between different network subnets.
- Configure network printers, servers, and IP phones.
- Test network connectivity using ping commands.
- Simulate a realistic office networking environment.

## 🗺️ Network Architecture

The network consists of six major areas:

| Area | Network Address | Connected Router |
|---|---|---|
| Reception Area | 194.168.10.0/24 | Router5 |
| Office 1 | 193.168.10.0/24 | Router4 |
| Office 2 | 195.168.10.0/24 | Router5 |
| Office 3 | 196.168.10.0/24 | Router6 |
| Security Area | 197.168.10.0/24 | Router6 |
| Server Room | 192.168.10.0/24 | Router4 |

### Network Components

- **Routers:** Router3, Router4, Router5, and Router6.
- **Switches:** Six switches for connecting devices in different areas.
- **PCs:** Desktop computers distributed across departments.
- **Servers:** Three servers located in the Server Room.
- **Printers:** Network printers for office operations.
- **IP Phones:** Voice communication devices.
- **Firewall:** Cisco ASA 5505 for the security area.

## ⚙️ Technologies & Protocols

| Technology | Purpose |
|---|---|
| Cisco Packet Tracer | Network design and simulation |
| Cisco IOS CLI | Router configuration |
| IPv4 Addressing | Device identification and communication |
| Subnetting | Network segmentation |
| RIP Version 2 | Dynamic routing |
| Ping | Connectivity testing |
| Ethernet | Wired network communication |
| Cisco ASA 5505 | Network security and firewall |

## 🌐 IP Addressing

The project uses static IP addressing to provide devices with consistent network configurations.

| Department | Device | IP Address | Default Gateway |
|---|---|---|---|
| Office 1 | PC | 192.168.10.10 | 192.168.10.1 |
| Office 2 | PC | 195.168.10.11 | 195.168.10.1 |
| Office 3 | PC | 196.168.10.12 | 196.168.10.1 |
| Server Room | Server | 193.168.10.100 | 193.168.10.1 |
| Security Area | PC | 197.168.10.13 | 197.168.10.1 |
| Reception | Printer | 194.168.10.50 | 194.168.10.1 |

**Subnet Mask:** 255.255.255.0

## 🔄 Dynamic Routing – RIP Version 2

RIP Version 2 is implemented to enable automatic route sharing between the connected routers.

It allows routers to exchange routing information and discover remote networks without manually configuring every remote route.

**Key Features:**
- Automatic route sharing.
- Communication between multiple subnets.
- Simplified routing management.
- Support for subnet masks through classless routing.
- Easier network maintenance and expansion.

## 🖥️ Router CLI Configuration

All four routers (Router3, Router4, Router5, and Router6) are configured using Cisco IOS Command Line Interface (CLI).

The repository includes the router configuration commands and their respective network settings.

### Router Configuration Details

| Router | Connected Networks |
|---|---|
| Router3 | 14.12.10.0 |
| Router4 | 192.168.10.0, 193.168.10.0, 11.12.11.0 |
| Router5 | 194.168.10.0, 195.168.10.0, 11.12.11.0, 13.12.10.0 |
| Router6 | 196.168.10.0, 197.168.10.0, 13.12.10.0, 14.12.10.0 |

The detailed CLI configurations are provided in the repository.

## 🧪 Network Testing & Verification

After completing the network configuration, connectivity tests were performed to verify communication between different devices and departments.

**Testing includes:**

- Ping tests between different office PCs.
- Communication between PCs and servers.
- Printer connectivity verification.
- Inter-network communication through routers.
- Verification of dynamic routing.
- IP phone functionality testing.

### Results

The network simulation successfully demonstrated communication between the connected office departments. Ping tests confirmed connectivity between PCs, printers, and servers, while RIP v2 enabled dynamic routing across the network.

## 📁 Project Contents

This GitHub repository contains the project resources, including:

- Cisco Packet Tracer project file (`.pkt`).
- Complete network topology.
- Router CLI configurations.
- IP addressing details.
- RIP v2 routing configurations.
- Network implementation and testing information.
- Project documentation and supporting materials.

## 🚀 How to Use

1. Download or clone this repository.
2. Install Cisco Packet Tracer.
3. Open the provided `.pkt` project file.
4. Explore the complete network topology.
5. Open individual routers to review their CLI configurations.
6. Examine the IP addressing and routing settings.
7. Use ping commands to test connectivity between network devices.

## 📚 Learning Outcomes

Through this project, we gained practical experience in:

- Enterprise network design.
- Cisco Packet Tracer simulation.
- Router and switch configuration.
- Cisco IOS CLI commands.
- IPv4 addressing and subnetting.
- Dynamic routing using RIP v2.
- Network troubleshooting.
- Network connectivity testing.

## 🔮 Future Improvements

The network can be further enhanced by implementing:

- VLANs for better departmental segmentation.
- Access Control Lists (ACLs) for traffic filtering.
- DHCP for automatic IP address allocation.
- Enhanced firewall security policies.
- Additional offices and network devices.
- Improved network monitoring and management.

## 🏁 Conclusion

The Office Management System project demonstrates the practical implementation of an interconnected enterprise network using Cisco Packet Tracer. By combining routers, switches, end devices, static IP addressing, and RIP Version 2, we successfully simulated communication across multiple office departments.

This project provides hands-on experience with networking concepts, Cisco CLI configuration, dynamic routing, and network troubleshooting.

---

**Project Type:** Computer Networking  
**Platform:** Cisco Packet Tracer  
**Routing Protocol:** RIP Version 2  
**Network Type:** Multi-Office Enterprise Network

**⭐ If you find this project useful, consider giving this repository a star!**
