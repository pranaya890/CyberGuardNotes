- 27 October 2026
- Internet Protocol Address or IP address is used to identify any device over the internet.
- IP address has two versions: IPv4 and IPv6 
## IPv4 
IPv4 is 32-bit address separated by (.), e.g. 192.168.10.1.
- It is divided into 4 sets and each set contains 8-bit. 
- IPv4 address : `********.********.********.********`
- Binary has 0 and 1. 
- 32-bit is 32 container to hold single binary values.
- 2^32 = 4.29B IPv4 address 
- Per octet - 2^8 = 256 : 
- 0-255 
- Index -      7      6   5   4   3 2 1 0 
- Decimal - 128 64 32 16 8 4 2 1 = 255 
- Binary -  1 1 0 0 0 0 0 0
``` Bash
#Commands to check IP Address 
# Windows 
ipconfig
#MacOS/Linux 
 ifconfig (ip a)
```

![[Pasted image 20261029195446.png]]


## Subnetting 
- Subnetting is dividing a big network into multiple small networks.
![[Pasted image 20261029195525.png]]

![[Pasted image 20261029195535.png]]

192.168.100.0
255.255.255.0 
Network Address: 192.168.100.0 
Broadcast Address: 192.168.100.255 
Host Address space: 192.168.100.1-254 

Ofiice-1 (64: 0-63) 
Network Address : 192.168.100.0 
Broadcast Address: 192.168.100.63 
Host Address space: 192.168.100.1-62 
Subnet Mask: 255.255.255.192

Ofiice-2 (64) 
Network Address : 192.168.100.64 
Broadcast Address: 192.168.100.127 
Host Address space: 192.168.100.65-126 
Subnet Mask: 255.255.255.192

Ofiice-3 (64)
Network Address : 192.168.100.128 
Broadcast Address: 192.168.100.191 
Host Address space: 192.168.100.129-190 
Subnet Mask: 255.255.255.192 

Ofiice-4 (64) 
Network Address : 192.168.100.192 
Broadcast Address: 192.168.100.255 
Host Address space: 192.168.100.193-254 
Subnet Mask: 255.255.255.192

