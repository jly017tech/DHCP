<h1>DHCP Server Scenario #1</h1>

<p>

What I have learned one of the labs from Testout is creating new scope in the DHCP server.
At the end of the lab, I go to one of the rooms (simulation map that that shows different networking closet room, Office room, lobby room and other rooms)
and clicked the laptop in the lobby.  
  

  
</p>

![image](https://github.com/user-attachments/assets/6d2cd180-82b5-4f90-bdf1-1ee54eb0d98e)


<P>  
  After clicking the DHCP server, I dropped down IPV4 options and created new scope. 
  I wrote Subnet and filled out both Start IP and End IP.
  192.168.0.20 for Start IP
  192.168.0.200 for End IP
</P>

![image](https://github.com/user-attachments/assets/d05082e2-8f1a-446d-9f84-3507d672170e)


![image](https://github.com/user-attachments/assets/6986d9f2-375b-434b-9534-fefb303f0061)

<p>
  I entered the default DHCP gateway so when a new computer connects to the Corp Wi-Fi and it will fill automatically out the IP address, subnet, and default gateway.

</p>


![image](https://github.com/user-attachments/assets/54687130-49f2-4852-a949-4f56000a3f72)


<p>

  I entered 163.128.78.93 for the DNS server
</p>


![image](https://github.com/user-attachments/assets/2dfeda7f-9859-491f-b4ce-c1008b1822b4)



![image](https://github.com/user-attachments/assets/d101f13e-57ab-4701-8fde-ab1d8ad993a1)


<p>

I changed manual to automatic in the networking setting and it replaces the old IP address, subnet, default gateway, and DNS Ip address.
After that, I used ipconfig /all and verified the GSPT laptop is connecting to the internet. 
  
</p>


![image](https://github.com/user-attachments/assets/616286b6-49bb-48ba-b555-1735a31ddf82)


  

