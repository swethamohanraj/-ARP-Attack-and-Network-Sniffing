# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## ALGORITHM:

1) Install kali linux either in partition or virtual box or in live mode

2) Investigate on the various categories of tools as follows:

3) Open terminal and try execute some kali linux commands


## METHODS:

### ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.

In windows 7 give the command arp -a

#### OUTPUT:

![image](https://github.com/Monisha-11/ARP-Attack-and-Network-Sniffing/assets/93427240/87a82952-db80-4a51-89fd-ada83f5b81f3)


### From kali linux issue the command : sudo arpspoof -i eth0 -t <target system> <gateway>

#### OUTPUT:

![image](https://github.com/Monisha-11/ARP-Attack-and-Network-Sniffing/assets/93427240/52a0a63d-e321-4522-8479-391ae948ef6f)


### dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

 
![image](https://github.com/Monisha-11/ARP-Attack-and-Network-Sniffing/assets/93427240/a4d03250-d53f-4175-9c6c-5028d8d098b8)


### In Kali issue the following commands:  sudo dsnifff

#### OUTPUT:

![image](https://github.com/Monisha-11/ARP-Attack-and-Network-Sniffing/assets/93427240/d64b6310-a901-49fd-a3f8-2d7c40f43509)

### Invoke the wireshark and examine the various menus and controls of the tool:

![image](https://github.com/Monisha-11/ARP-Attack-and-Network-Sniffing/assets/93427240/676e5a23-72d5-4f77-8ec5-aad43a605b6d)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
