# hyperv-infrastructure-lab
Enterprise infrastructure homelab using Hyper-V, Windows Server 2012, Active Directory, iSCSI storage.
# Network Engineering Homelab

## Overview
This project documents my enterprise infrastructure lab built to practice real-world system administration and network engineering tasks.

## Technologies

Hypervisor:
- Hyper-V

Operating Systems:
- Windows Server 2012
- Windows 11

Services:
- Active Directory
- iSCSI Storage
- File Server

Backup:
- Altaro VM Backup

## Lab Architecture

Laptop Host (Hyper-V)
│
├── DC01 - Domain Controller
├── SAN01 - iSCSI Storage
├── FS01 - File Server
└── WIN11 - Client Machine

## Network Plan

LAN: 192.168.10.0/24  
Storage Network: 10.10.10.0/24

## Objectives

✔ Build enterprise virtualization lab  
✔ Deploy Active Directory domain  
✔ Configure file services  
✔ Implement backup solution  
✔ Test file-level restore
