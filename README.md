# Windows Server 2022 Administration Lab

## Overview
I built a virtual Windows Server 2022 environment to practice core server tasks used in IT support and systems administration.

## Environment
- Windows Server 2022 virtual machine
- Windows client virtual machine joined to the domain
- Private virtual network (no real company data)

## What I Configured
### Active Directory
- Installed Active Directory Domain Services and created a domain.
- Created organizational units, user accounts and groups.
- Joined a client computer to the domain.

### DNS
- Set up DNS for the domain.
- Confirmed name resolution with `nslookup`.

### DHCP
- Installed the DHCP role and created an IP address scope.
- Confirmed the client received an address with `ipconfig /all`.

## What I Learned
- How Active Directory, DNS and DHCP depend on each other.
- How to check each service when a client cannot join the domain.

## Security Note
Screenshots leave out passwords and sensitive settings.
