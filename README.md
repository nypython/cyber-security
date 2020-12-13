# cyber-security
project 1 ## ELK server with Azure  
deployed a jumbox connect public internet.
configure two virtual machines which use private addresses to interface with jumbox 
within the virtual machines #1 and #2, installing docker with yaml file that modified host and filebeat yaml file.
after the installed, ensured the connection is connected. 
installing another docker with yaml file that modified host and filebeat & metricbeat configuration yaml file.
deployed the elk server VM to monitor the log events. 


project 2 ## pen testing 
kali is attack machine, capstone is target machine and elk is the machine that capture the log events
using nmap scaned all the ports to check which are opens.
for the known IP address, copy and paste in the URL to check any useful information through the web.
traveral the URL directory for hidden files
after gained the user's information, open metasploit to crack the password associate with users. 
with that information, logging to the webdav server
uploading the backdoor for persistent attack further.


final project ## combination of project #1 and project #2
the TA team already built up target VMs and elk server VM for log events.
for what our teams doing, we first gather some information from the target VMs, and starting a attack strategies.
first, scan for target, then find out open ports. after that, using metasploit for port 22 ssh to gain access.
john of the rippler for brute force of password.
after several steps, we find out the flags. 
