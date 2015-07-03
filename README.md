###Sockets

Sockets are used for communicating with other programs with the help of Unix file descriptors. 

There are two types of sockets
* Stream sockets (SOCK_STREAM)
* Datagram sockets (SOCK_DGRAM)

Stream sockets are mainly used in two way communication. If you send A, B, C through stream socket it will arrive in that particular order. Stream sockets are error free meaning data you send would be always recieved at the other end without any error. This is achived with the help of TCP (Transmission Control Protocoal). TCP makes sure that the data which has arrived is sequential and error free. This feature make stream sockets reliable.  

Datagram socket unlike Stream sockets is not reliable. The data arrives in no particular order. The advantage of Datagram sockets over stream sockets is the absence of an open connection at the time of transmission. The only thing you need to do is 

