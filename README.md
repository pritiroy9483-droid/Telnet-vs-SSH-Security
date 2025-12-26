Comparative Security Analysis of Telnet and SSH Using Network Traffic Capture

* PROJECT OVERVIEW

This project focuses on the comparative security analysis of Telnet and SSH
protocols using network traffic capture techniques. The objective of this
project is to demonstrate how Telnet transmits data in plain text, making it
vulnerable to packet sniffing attacks, while SSH provides secure and encrypted
communication.
The experiment is performed in a controlled environment using Kali Linux and
Wireshark. Network packets are captured during Telnet and SSH login sessions
and analysed to observe the visibility of credentials and commands.
Through this practical analysis, the project highlights why Telnet is
considered insecure and why SSH is widely used as a secure remote access
protocol in modern cyber security environments.

* OBJECTIVES
  
 1 To configure and demonstrate Telnet service on a Kali Linux system

 2 To capture Telnet traffic using Wireshark
3 To analyse plain-text transmission of usernames, passwords, and commands
4 To configure and demonstrate SSH service on the same system
 5 To capture and analyse encrypted SSH traffic
6 To perform a comparative security analysis of Telnet and SSH
7To simulate a real-world network sniffing attack scenario

* LAB ENVIRONMENT

SERVER MACHINE
    1  operting system: kali linux
    
    2 servies
         TELNET(in.telnetd)
         openSSH (sshd)

  ATTACKER MACHINE
  
     host machine (windows/ linux)
     TOOL USE
        telnet client
        ssh client
        wireshark

  *METHODOLOGY
  Telnet service was configured and activated on the Kali Linux system
Network traffic was captured during Telnet login and command execution
Packet analysis confirmed that credentials and commands were visible in plain text
SSH service was configured and activated on the same system
SSH traffic was captured using Wireshark Packet analysis showed encrypted and unreadable payload data
A comparative analysis was performed to highlight security differences

*OBSERVATIONS AND RESULTS

Telnet transmits usernames, passwords, and commands in plain text
Telnet traffic can be easily sniffed by an attackerSSH encrypts all communication, preventing data disclosure
SSH packets do not reveal sensitive information even when captured

*CONCLUSION
The experiment proves that Telnet is highly vulnerable to network sniffing attacks, while SSH provides strong security through encryption. This analysis highlights the critical role of secure protocols in modern network security.

* AUTHOR

1PRITI KUMARI

2 B.TECH CYBERSECURITY STUDENT

3RUNGTA COLLEGE OF ENGINEERING AND TECHNOLOGY


