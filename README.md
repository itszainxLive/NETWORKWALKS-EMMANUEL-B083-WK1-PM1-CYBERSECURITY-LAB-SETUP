# NETWORKWALKS-EMMANUEL-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
Cybersecurity Lab Environment Setup using VirtualBox and Kali Linux
# 🔐 Cybersecurity Lab Environment Setup

**Building a virtual cybersecurity lab using Oracle VirtualBox and Kali Linux**

---

## 📌 Project Overview

This project focuses on setting up a basic virtual cybersecurity laboratory using **Oracle VirtualBox** and **Kali Linux**.

The lab will provide a controlled environment for learning cybersecurity concepts and performing authorized security-testing activities.

---

## 🎯 Objectives

- Install 7-Zip.
- Install Oracle VirtualBox.
- Create a private NAT Network.
- Configure the lab network as `10.0.0.0/24`.
- Add Kali Linux to VirtualBox.
- Configure the Kali virtual machine.
- Document the setup process with screenshots.
- Prepare the environment for future cybersecurity exercises.

---

## 🛡️ Ethical Use

This laboratory is intended for **educational and authorized security testing only**.

Only test systems that you own or have explicit permission to test.

---

# 🪜 Lab Setup Procedure

## Step 1 — Install 7-Zip

7-Zip was installed to extract and manage compressed virtual-machine files.

### Screenshot

![7-Zip Installation](screenshots/01-7zip-installed.PNG)

---

## Step 2 — Install Oracle VirtualBox

Oracle VirtualBox was installed and opened successfully.

VirtualBox is being used as the hypervisor for the cybersecurity laboratory.

### Screenshot

![VirtualBox Manager](screenshots/02-virtualbox-installed.png)

---

## Step 3 — Create the NAT Network

A dedicated NAT Network named **NatNetwork** was created in VirtualBox.

### Network Configuration

| Setting | Value |
|---|---|
| Network Name | `NatNetwork` |
| IPv4 Prefix | `10.0.0.0/24` |
| DHCP | Enabled |
| IPv6 | Disabled |

The NAT Network will allow virtual machines connected to the same network to communicate with each other while providing NAT-based network connectivity.

### Screenshot

![NAT Network Configuration](screenshots/03-nat-network.png)

---

## Step 4 — Add Kali Linux to VirtualBox

An existing **Kali Linux 2025.4** VMware virtual disk was attached to a new VirtualBox virtual machine.

The original virtual disk used for the VM is:

```text
kali-linux-2025.4-vmware-amd64.vmdk
