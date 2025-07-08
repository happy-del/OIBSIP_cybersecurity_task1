# OIBSIP_cybersecurity_task1

NMAP - Network Mapper
Purpose - Used for network discovery and security auditing.

1. nmap <domain_name> : To perform Nmap scan on domain, you can use domain name directly in Nmap command. Nmap will then resolve domain name to its corresponding IP address and perform the scan.
Example : nmap scanme.nmap.org - The command scans the domain scanme.nmap.org.

The attached output is the Nmap scan for **scanme.nmap.org.**  
1. The scan first checks if the host is up and it shows that the host was up with 0.42s latency.It also mentions the ip address of host i.e. 45.33.32.156.
**Nmap scan report for scanme.nmap.org (45.33.32.156)
Host is up (0.42s latency).**

2.Then Nmap scan detect for open ports, the output only shows the open ports that are detected. 
As per the output,the scan has discovered 4 open ports with their services. 
For example: 22/tcp port is running services for secure shell remote access. 
              80/tcp port is a web service.
              9929/tcp port used by nmap tool.              
**PORT      STATE SERVICE
22/tcp    open  ssh
80/tcp    open  http
9929/tcp  open  nping-echo
31337/tcp open  Elite**
**Not shown: 996 filtered tcp ports (no-response)** This output means Nmap has not receive response from these ports.
