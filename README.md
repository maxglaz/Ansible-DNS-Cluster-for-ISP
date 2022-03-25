# Ansible-DNS-Cluster-for-ISP
DNS Cluster solution for Internet Service Providers. <br>
<br>
<b>Solution Parts</b><br>
1.Recursive DNS Cluster.<br>
2.Authiritative Slave DNS Cluster.<br>
3.Authiritative Master DNS server + Web-UI.<br>
<br>
<b>Starting environment</b><br>
1.Servers with minimal installation of AlmaLinux 8.5+ (tested environment, but i believe it could be used with another Linux ditro, after slight ajastments).<br>
2.Server with installed Ansible<br>
<br>
<b>Part 1. Recursive DNS Cluster.</b><br>
Schematic: Customer -> (Public IP)-Load Balancer-(Private IP) -> Server Cluster<br>
Note1: You can either limit clients whos DNS-requests will be processed either with ACL at server (included in this solution) or with Load Balancer <br>
Note2: To decrease chances of critical fault due to software update, i`ll use two different DNS servers (PDNS & Unbound) to create cluster.<br>
<br>
<b>Configuration & Installation</b>
Pending...
