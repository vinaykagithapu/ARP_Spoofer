# ARP_Spoofer
### What is ARP Spoofing?
#### ARP spoofing allow us to redirect the flow of packet and make us Man In The Middle (MITM).
####
### Why ARP spoofing is possible?
#### 1. Clients accept response even if they did not send a request.
#### 2. Clients trust response without any form of verification.
####
### "It Works for only Linux"
#
### Requriments:
```
sudo apt-get install python
sudo pip install scapy
```
#
### Usage:
```
sudo python arp_spoof.py
Target IP : Give IP  address of Target
Gateway IP : Give IP addresss of Gateway
[ Ctrl+C ] To stop
```
