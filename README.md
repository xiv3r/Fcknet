# FckNet

FckNet is a versatile network manipulation tool that utilizes **Scapy** for all its features, enabling users to perform various network-related tasks. It supports several functionalities, including ARP spoofing, DHCP starvation, network scanning, and SYN flooding.

## Features

- **ARP Spoofing**: Intercept and redirect network traffic by sending fake ARP packets.
- **DHCP Starvation**: Flood the DHCP server with requests to exhaust its available IP addresses.
- **Network Scanning**: Discover active devices on a network and retrieve their IP and MAC addresses.
- **SYN Flooding**: Launch a SYN flood attack to overwhelm a target system.

## Usage

1. Run Fcknet with Root Privilege:
   ```
   sudo python3 fcknet.py
   ```

2. Available Commands:
- **arp_spoof:** Execute ARP Spoofing.
- **dhcp_starv:** Conduct DHCP Starvation.
- **net_scan:** Perform a Network Scan.
- **syn_flood:** Initiate a SYN Flood Attack.
- **help or h:** Display the list of commands.
- **exit or quit:** Terminate the program.

## Requirements
- Root Access: FckNet requires root privileges to perform its functions.
- Python 3: Ensure that Python 3 is installed on your system.
- Scapy: Ensure you have Scapy library installed because Scapy is the root core of this tool. (pip3 install scapy)

