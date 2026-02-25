# analyzenetwork

Analyze Network Application Services

Looking through packets and identifying what is going on. 

FTP – source 10.15.1.80 is trying to connect to a server that has the Ip of 10.15.1.50. it is a student logging into the server. Both the servers are on VMware as signified by their MAC address. A three-way handshake has been established between them also.

 <img width="767" height="260" alt="image" src="https://github.com/user-attachments/assets/c5086b5b-6e92-4a3c-bd9b-031ac069615b" />

SSH – there’s a client and server communication between them and it seems to be encrypted with elliptic curve Diffie Hellman cypher as security

 <img width="744" height="450" alt="image" src="https://github.com/user-attachments/assets/2eccdf29-6586-44bd-8288-fb7374327bfb" />

SMTP – no packets to observe 

 <img width="956" height="173" alt="image" src="https://github.com/user-attachments/assets/18b6702d-d299-46c6-9129-56f856848150" />

IMAP – this is an email server it contacted the server then got a response check. It went into the inbox folder. 

 <img width="790" height="287" alt="image" src="https://github.com/user-attachments/assets/1a2102d1-58a6-45e1-a64e-677574b1fe00" />

SMB – this is a Microsoft server and it is on an NT workstation. It isn’t a domain controller, or a novel or apple host. 

 <img width="775" height="482" alt="image" src="https://github.com/user-attachments/assets/f955346a-45f1-460c-bf37-36299499e5b2" />

Telnet – this server was logged into on October 10th from 10.15.1.50

 <img width="720" height="373" alt="image" src="https://github.com/user-attachments/assets/b881aa5e-c840-4546-83c7-535d4927ee39" />

