# NETWORKWALKS-GLORY-PAUL-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP

# NETWORKWALKS-GLORY-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP

# WK1-PM1 — Cybersecurity Lab Setup

## 1. Project Overview

This project involved setting up a cybersecurity testing lab using Oracle VirtualBox and Kali Linux. The purpose was to prepare a virtual environment for future cybersecurity and ethical hacking practical exercises.

## 2. Tools Used

- **Oracle VirtualBox:** To run and manage virtual machines.
- **Kali Linux:** Used as the cybersecurity testing machine.
- **7-Zip:** Used to extract the downloaded Kali Linux virtual machine archive.

## 3. Network Configuration

The Kali Linux virtual machine was configured to use a custom VirtualBox NAT Network.

| Setting | Configuration |
|---|---|
| Network Name | CyberLab |
| Network Subnet | `10.0.0.0/24` |
| Network Interface | `eth0` |
| Kali Linux IP Address | `10.0.0.2/24` |
| Default Gateway | `10.0.0.1` |
| DNS Servers | `1.1.1.1`, `8.8.8.8` |

## 4. Configuration Steps

### Step 1: Install the Required Software

Installed Oracle VirtualBox and 7-Zip on the host computer.

### Step 2: Create the NAT Network

Created a custom VirtualBox NAT Network named `CyberLab` using the subnet `10.0.0.0/24`.

### Step 3: Install and Configure Kali Linux

Downloaded and imported the Kali Linux virtual machine into VirtualBox. Configured its network interface, `eth0`, with the required static IP address `10.0.0.2/24`.

### Step 4: Verify Internet Connectivity

Tested connectivity to the default gateway, an external IP address, and a domain name to verify network and DNS access.

### Step 5: Configure Shared Resources

Enabled a shared folder to access the host computer's Downloads directory from Kali Linux. Configured bidirectional clipboard and drag-and-drop in the VirtualBox settings.

### Step 6: Create a Snapshot

Created a VirtualBox snapshot to preserve the configured virtual machine for recovery and future practical exercises.

## 5. Screenshots and Evidence

The following screenshots provide evidence of the lab configuration.

### VirtualBox Manager
![VirtualBox Manager](screenshots/Screenshot-1.png)

### NAT Network Configuration
![NAT Network Configuration](screenshots/Screenshot-2.png)

### Kali Linux IP Configuration
![Kali IP Configuration](screenshots/Screenshot-3.png)

### Internet Connectivity Tests
![Internet Connectivity](screenshots/Screenshot-4.png)

### Shared Folder Configuration
![Shared Folder](screenshots/Screenshot-5.png)

### Virtual Machine Snapshot
![Kali Snapshot](screenshots/Screenshot-6.png)

## 6. Troubleshooting Experience

During the setup, I encountered an issue accessing the shared Downloads folder from Kali Linux. I checked the shared-folder configuration in VirtualBox and corrected the setup until the folder became accessible.

I also verified the Kali network configuration and tested internet connectivity to ensure the virtual machine could communicate with the network.

## 7. Learning Outcomes

Through this project, I learned how to:

- Install and manage a Kali Linux virtual machine using VirtualBox.
- Configure a custom NAT Network and static IPv4 address.
- Test internet and DNS connectivity.
- Configure shared folders and host-to-guest integration.
- Use snapshots to preserve a working virtual machine configuration.

## 8. Conclusion

The WK1-PM1 lab setup provided a foundation for future cybersecurity and ethical hacking practical exercises. The configured Kali Linux environment can be used for authorized testing and learning in a controlled lab.



Student Name: Glory Paul
Course/Week: WK1-PM1  
Project: Cybersecurity Lab Setup
