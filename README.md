# Small Office LAN Network Design (Cisco Architecture)

## Project Overview

This project involves the design and logical configuration of a secure Local Area Network (LAN) for a small office environment. The architecture follows a Star Topology and integrates security layers to ensure data integrity and controlled access.

## Technical Specifications

- **Topology:** Star Topology
- **Gateway:** Cisco Router (IP: 192.168.1.1)
- **Security:** Integrated Cisco Firewall & VLAN Segmentation (Office vs. Guest)
- **Core Switching:** Cisco Managed Switch
- **Services:** Centralized Data Server (DHCP, DNS, File Storage)
- **Connectivity:** Ethernet (Workstations) and Wireless (Access Point)

## Network Diagram

![Network Diagram](./your_image_name.png)
_(Note: Replace "your_image_name.png" with the actual filename you uploaded)_

## Key Features

1.  **Automated Addressing:** Implementation of DHCP on the Data Server to manage IP distribution for workstations.
2.  **VLAN Segmentation:** Logical separation of traffic to enhance security and reduce broadcast domains.
3.  **Scalability:** The design allows for the addition of more end devices via the core switch without disrupting current services.
