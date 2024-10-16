# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

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
```
Tested By : Shaik Sameer Basha
Reg. No: 212222240093
```
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![img1](https://github.com/user-attachments/assets/a659dbd6-98d3-4b41-9d4c-0fb614664657)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

![img2](https://github.com/user-attachments/assets/fe522e80-b2bf-4ba3-ac62-12c028d37348)

## OUTPUT:

In Kali issue the following commands:
sudo dsnifff
![img3](https://github.com/user-attachments/assets/9d5e10eb-f6e5-4c57-9936-f409ec960833)

## OUTPUT:

![img4](https://github.com/user-attachments/assets/ead19044-d491-4682-9d98-ba3083e8fb14)

Invoke the wireshark and examine the various menus  and controls of the tool:

![img5](https://github.com/user-attachments/assets/6b4a9a07-8310-463c-862d-c2f6dae26fe2)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
