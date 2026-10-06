Nmap Network Reconnaissance Lab

Objective
The objective of this lab was to practice network reconnaissance using Nmap and identify the open ports,services,service versions and operating system information of a ddeliberately vulnerable Metasploitable virtual machine

Lab Environment
Component        Details
Attacker Machine-Kali Linux
Target Machine-  Metasploitable2
Target IP-       192.168.93.252
Kali IP-         192.168.93.30
Network-         192.168.93.0/24
Virtualization-  Virtual box

Tools used
-Kali Linux
-Nmap
-Metasploitable2
-VirtualBox

Methodology
The reconnaissance was performed in 3 stages
1. Basic port scanning
2. Service and version detection
3. Operating system detection

All scanning was performed against my own Metasploitable virtual machine in a controlled lab environment.

Commands used
1. Basic Port Scan
nmap 192.168.93.252

This scan was used to identify TCP ports that were open on the target.

2. Service and Version Detection
nmap -sV 192.168.93.252

This scan was used to identify the probable operating system and kernel version of the target.

Results
The basic Nmap scan identified 23 open TCP ports on the Metasploitable machine.

Some of the services identified included:
Port Service   Version
21   FTP       vsftpd2.3.4
22   SSH       OpenSSH 4.7p1
23   Telnet    Linux telnetd
25   SMTP      Postfix
53   DNS       ISC BIND 9.4.2
80   HTTP      Apache 2.2.8
139  NetBIOS   Samba
445  SMB       Samba
3306 MySql     MySQL 5.0.51a
5432 PostgreSQL PostgreSQL8.3x
5900 VNC        VNC protocol 3.3
8180 HTTP       Apache Tomcat

The operating system detection identified target as:

Linux 2.6x

Nmap estimated the network distance as 1 hop

Findings
The reconnaissance revealed that the target machine exposes a large number of network services.

The most important observations were:
-Multiple network services were accessible
-Several older software versions were identified
-FTP,Telnet,HTTP,SSH,database,SMB,VNC and other services were running.
-The large number of exposed services provides a useful environment for studying vulnerabilities assessment in a controlled lab.

Security Observations
Exposing unnecessary services can increase the attack surface of a system.

Service and version enumeration is useful during security assessment because it helps identify technologies that may require further security assessments beacuse it helps identify technologies that may require further security investigation,patching,configuration review or vulnerability assessment.

Lessons Learned
This lab helped me understand:
-How Nmap identifies open ports.
-The difference between port scanning and service enumeration.
-How -sV can identify service versions.
-How -O can help identify the operating system.
-How reconnaissance provides information for later security assessment activities.
-The importance of performing security scans only against systems I own or have permissions to test.

Conclusion
The Nmap reconnaissaince lab successfully identifies the exposed network services and operating system characteristics of the Metasploitable target.
This exercise provided practical experience with network reconnaissance and established a  foundation for future vulnerability and security investigation labs.


