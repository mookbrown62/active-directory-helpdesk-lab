# Active Directory Help Desk Lab

## Project Overview

This project demonstrates a hands-on IT Help Desk environment using Windows Server, Active Directory Domain Services, and ServiceNow.

The lab simulates common Level 1 Help Desk responsibilities including user account administration, password resets, Active Directory troubleshooting, and incident documentation.

## Technologies Used

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS
- Active Directory Users and Computers (ADUC)
- ServiceNow
- Microsoft Azure
- macOS

## Lab Environment

**Domain:** mooklab.local  
**Domain Controller:** DC01

Organizational Units (OUs) were created to simulate departments within an organization:

- IT
- HR
- Sales
- Accounting

## Help Desk Scenario #1 — Password Reset

### Issue

A user reported being unable to log into their domain account because of a password issue.

### Troubleshooting & Resolution

1. Received and documented the incident in ServiceNow.
2. Located the user's account in Active Directory Users and Computers.
3. Verified the account status.
4. Performed a domain password reset.
5. Configured the account to require a password change at next logon.
6. Documented troubleshooting steps in ServiceNow work notes.
7. Added resolution notes.
8. Resolved the incident after restoring account access.

## Skills Demonstrated

- Active Directory administration
- User account management
- Password resets
- Organizational Unit management
- Windows Server administration
- ServiceNow incident management
- Ticket documentation
- Troubleshooting
- Technical documentation

## Future Labs

Additional Help Desk scenarios will be added to this repository, including account lockouts, user provisioning, group membership, permissions, and other common IT support issues.
