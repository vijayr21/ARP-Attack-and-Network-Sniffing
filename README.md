# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

## Developed By : VIJAY R
## Register No  : 212223240178

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/user-attachments/assets/7c213815-74d4-4030-8ea7-1d09ad7eabf0)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/3c4af8b5-69cb-47cc-87af-c29ff4937986)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org


## OUTPUT:

![image](https://github.com/user-attachments/assets/868ffd08-184c-436a-a25e-3b08e3d907d3)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/user-attachments/assets/3c0b81b6-83ec-466b-be0a-feed223a9517)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/6cf70955-c919-4cf3-a550-1065f967e6fa)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
