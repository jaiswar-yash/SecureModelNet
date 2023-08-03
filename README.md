# Secured Network with Subnetting of Class C (Cisco Packet Tracer)

## Overview

This GitHub repository contains the documentation and configuration files for setting up a secured network with subnetting of Class C IP addresses. The network is designed and simulated using Cisco Packet Tracer to demonstrate the implementation of various security measures, including port security, Access Control Lists (ACL), and Variable Length Subnet Masking (VLSM). Additionally, the network incorporates a DHCP server to dynamically assign IP addresses to devices within one of the subnetworks. The setup consists of three routers, each with its own switch, and the DHCP server is connected to the third switch.

## Table of Contents

1. Subnetting
2. Port Security
3. Access Control Lists (ACL)
4. Static IP Addressing
5. Configuration Files
6. Tasks
7. Usage
8. Contributing

## Subnetting

The Class C IP address space is efficiently divided into smaller subnets using Variable Length Subnet Masking (VLSM) within Cisco Packet Tracer. This allows for optimal utilization of IP addresses and provides separate networks for different departments or purposes.

## Port Security

Port security is implemented on the switches within Cisco Packet Tracer to control access to the network by allowing only specific devices to connect to individual switch ports. Unauthorized devices attempting to connect will be blocked, enhancing network security.

## Access Control Lists (ACL)

Access Control Lists (ACL) are applied to routers within Cisco Packet Tracer to filter network traffic based on specific criteria. This restricts access to sensitive resources and prevents unauthorized communication between different subnetworks.

## Static IP Addressing

Two of the subnetworks connected to the switches are configured with static IP addressing. This ensures that specific devices have fixed IP addresses, which is essential for network stability and proper functioning of certain services.

## Configuration Files

All configuration files for routers, switches, and the DHCP server can be found in the `configurations/` directory of this repository.

## Tasks

The network setup follows the following tasks:

1. Using IP 180.100.0.0/16, divide IPs for the users 3000, 500, and 20 respectively using VLSM (Variable Length Subnet Masking).
2. Apply routing, ACL (Access Control List), port security on the following PCs:
   - PC1: Cannot communicate with the server.
   - PC5: Cannot connect through HTTP.
   - PC4: Cannot connect through FTP.
   - PC3: Apply port security.

## Usage

To replicate this network setup in your own Cisco Packet Tracer environment, refer to the `Secured Network POC.pdf` document for step-by-step instructions.

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or encounter any issues, please feel free to submit a pull request or open an issue.

---

**Note:** This README file provides an overview of the network setup, the tasks being followed, and the resources available in this repository. For detailed step-by-step instructions, refer to the `Secured Network POC.pdf` document.
