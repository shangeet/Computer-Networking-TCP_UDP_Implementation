# CS3251HW2Project
Members:
Shantanu Mantri
Darren Leung
Jason Wu

Computer Networking Project 2 UDP Reliable Implementation
This is an implementation of Reliable UDP Transfer. 
RTPClient sends a file to RTPServer, which then changes the file. Both are simultaneously sending and receiving. 

To Run:
javac *.java
java RTPServer Portnum Winsize  (e.g. java RTPServer 4000 5)

python3 RTPClient.py serverhost Portnum Winsize (e.g. python3 RTPClient.py networklab3 4000 5)
 
Commands: 
Client:
transfrom filename (e.g. transform test.txt)
disconnect