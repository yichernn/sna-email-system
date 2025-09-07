# Simple Email & Web Services (SNA Assignment)

A System and Network Administration (SNA) project developed in **Rocky Linux (server)** and **Ubuntu Linux (client)** using **VirtualBox**.  
This project demonstrates the configuration of essential network and server services for a small organization, including an **Email System, NFS File Sharing, Apache Web Server, SSL/TLS, and an additional service**.  

---

## Part 1: Secure Email System
Configured a secure email server-client environment to allow encrypted communication between users.

### Features
- Configured network settings (FQDN, static IP, DNS, DHCP)  
- Installed and configured Postfix (Mail Transfer Agent)  
- Installed and configured Dovecot (IMAP/POP3 server)  
- Implemented SSL/TLS encryption for secure mail transfer and retrieval  
- Integrated with Mozilla Thunderbird on the Ubuntu client  
- Successfully exchanged emails securely between client and server  

### Tools & Technologies
- Rocky Linux (server), Ubuntu (client)  
- Postfix, Dovecot  
- OpenSSL  
- Mozilla Thunderbird  

---

## Part 2: Server & Web Services
Extended the server setup with web, file-sharing, and SSL/TLS support to simulate a small organizational environment.

### A. Network Configuration
- Set FQDN hostnames for server and client  
- Configured static IP addressing on Rocky Linux server  

### B. Network File System (NFS)
- Created and exported a shared NFS directory on the server  
- Configured Ubuntu client to mount and access the NFS share  
- Demonstrated successful file sharing between client and server  

### C. Apache Web Server
- Installed and configured Apache Web Server  
- Hosted multiple websites with separate directories and `index.html` pages  
- Configured Virtual Hosts for multi-site hosting  
- Verified site access from Ubuntu client via browser  

### D. SSL/TLS with Certificate Authority (CA)
- Installed and configured OpenSSL  
- Created a Certificate Authority (CA) and distributed public certificates  
- Configured Apache with HTTPS support  
- Verified secure connections from Ubuntu client  

### E. Additional Service
- Implemented and configured an extra service (e.g., FTP, DNS, or Firewall) to extend system capabilities  
- Tested functionality from Ubuntu client  

---

## Technologies Used
- VirtualBox (virtualization platform)  
- Rocky Linux (server), Ubuntu Linux (client)  
- Postfix, Dovecot (email services)  
- Apache (web server)  
- NFS (file sharing)  
- OpenSSL (SSL/TLS support)  
- Thunderbird (email client)  

---

## Learning Outcomes
- Gained practical experience in Linux system and network administration  
- Configured and secured an enterprise-style Email Server  
- Set up NFS file sharing between server and client  
- Deployed and hosted multiple websites with SSL/TLS encryption  
- Strengthened troubleshooting and security configuration skills in real-world network services  
