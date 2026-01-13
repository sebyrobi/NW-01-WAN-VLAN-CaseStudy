# NW-01-WAN-VLAN-CaseStudy

Project: Enterprise-style network setup  
Skills: Routing, Switching, VLANs, InterVLAN Routing, Trunks (802.1Q), EtherChannel (LACP), DHCP, Device Hardening  
Grade: 97%  

## Project Overview

This project is a full enterprise-style network built in Cisco Packet Tracer. I configured:

- Router interfaces for WAN and LAN, including sub-interfaces on the Vargas router
- VLANs and interVLAN routing using Router-on-a-Stick
- Switch access ports, trunks, and LACP EtherChannel between Switch 1 and Switch 2
- DHCP on the router for VLAN 10 and VLAN 20 hosts, excluding the first 10 IPs for servers/printers
- Standard device housekeeping, including hostname setup and MD5 password encryption
- Verified connectivity across all devices

The topology was provided in the assignment, but I also recreated it myself. Both diagrams are included in the `diagram/` folder to show I can reproduce and understand the network independently.  

The Packet Tracer file `Case Study PT (Final).pkt` is included for full review.

## Instructions / How to Review

1. Open the Packet Tracer file `Case Study PT (Final).pkt` to explore the network layout and verify configurations.
2. Check the `configs/` folder to see router, switch, and server configuration files.
3. Review the `diagram/` folder for both the original topology and my own recreation.
4. Look at the `screenshots/` folder to verify connectivity, VLANs, DHCP, and trunk/EtherChannel functionality.
5. PCs in VLAN 10 and VLAN 20 are set to obtain IP addresses automatically via DHCP. VLAN 99 hosts are configured manually.

## Supplementary Files

The `supplementary/` folder includes reference checklists for this case study:

- `Case Study CNVT 1820 Summer 2022(1).html` – full overview of assignment tasks  
- `CNVT1820 Case Study Phase CHECKLIST.html` – condensed version / minimum requirements  

These files provide context for the assignment scope and verification steps.
> Note: ACLs listed in the checklists were not required and were not implemented.

## Key Takeaways

- Demonstrates practical CCNA-level skills in routing, switching, VLANs, DHCP, and network device setup
- Shows ability to reproduce a network from instructions and verify it works end-to-end
- Screenshots provide evidence of working interVLAN routing, DHCP assignment, and trunk/EtherChannel setup
- Devices were configured following industry-standard setup and housekeeping practices
