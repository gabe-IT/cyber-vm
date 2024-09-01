# Azure Lab Setup Guide

This guide will walk you through setting up an Azure environment with a Windows 10 Pro and an Ubuntu virtual machine (VM). These VMs will be used in subsequent labs. This lab will not include much visual documentation as I have previously demonstrated how to provision a virtual machine on my portfolio. That can be found [here.](https://github.com/gabe-IT/azure-vm) 

## Prerequisites

- **Azure Account**: Create a new Azure account using [this link](https://azure.microsoft.com/en-us/free/). Avoid using a work or school account.
- **Azure Subscription**: Try to create a free subscription. If you're unable to, consider using a different credit card, email, and phone number to get another free one. Alternatively, sign up for a "pay as you go" account, opting for the free support tier to minimize costs. Remember to keep your VMs off when not in use to avoid unnecessary charges.

## Steps to Setup

### 1. **Create a Windows 10 Pro VM**
   - **Region**: EAST US 2
   - **Resource Group**: RG-Cyber-Lab
   - **VM Name**: `windows-vm`
   - **Virtual Network**: `Lab-VNet`
   - Choose an appropriate VM size that is cost-effective.
   - Set a strong password for the VM.

### 2. **Create an Ubuntu (Linux) VM**
   - **Region**: EAST US 2
   - **Resource Group**: RG-Cyber-Lab
   - **VM Name**: `linux-vm`
   - **Virtual Network**: `Lab-VNet`
   - Avoid using the B1s size; select a larger option.
   - Use username and password for authentication.

### 3. **Configure Network Security Groups (NSGs)**
   - For both VMs, configure the NSGs (Layer 4 Firewall) to allow all inbound traffic.

### 4. **Record Your Information**
   - Document all relevant subscription and VM details in a notepad for future reference.

## Next Steps

The VMs will be used in the next lab. You can leave them on unless you are done for the day.
