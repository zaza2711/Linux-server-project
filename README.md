# Linux-server-project
Linux server setup with networking basics and documentation

## 🎯 Project Objective
The goal of this project is to set up and secure a Linux server in order to
understand Linux administration, networking fundamentals, and basic server security.

## 🛠️ Technologies Used
- Ubuntu Server 24.04 LTS
- SSH
- Apache Web Server
- UFW Firewall
- Bash/Shell scripting

## 🔧 What I Did
- Installed Ubuntu Server on a virtual machine
- Created and managed Linux users
- Configured SSH for remote server access
- Installed and tested Apache web server
- Configured firewall rules using UFW
- Performed basic network tests
- Real-time monitoring of system processes using top and htop
- Integrated automation tools providing a real-time dashboard (Disk, RAM, Services) and scheduled web-content backups to timestamped directories

## 🌐 Networking Basics
- IP addressing (private IPs)
- DNS name resolution
- HTTP client-server communication
- Difference between localhost and network IPs
- Using SCP (Secure Copy) to deploy content from my Mac to the Linux server

## 🧪 Commands Examples
```bash
sudo apt update
sudo apt install apache2
sudo ufw allow ssh
sudo ufw allow http
chmod +x backup_web.sh
./backup_web.sh
ping google.com
