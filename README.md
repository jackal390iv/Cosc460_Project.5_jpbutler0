Cosc460_Project.5_jpbutler0
===========================

So this program is ment to make a TCP connection using ServerSockets/Sockets; with this connection it will deliver a simple "Hello World" message to the client pc. However as I have only tested on one computer and have had buggs... Imm willing to bet it doesn't work as intended... I have made a threaded chat program with datagramsockets before(UDP) and it has worked fine but this seems to have been giving me issue... I feel the problem lies in how I have threaded my program, and I feel unfarmilliar enough with threads to know how to fix it.. What the program should be doing is creating a socket, displaying the port and ip address to the user, then threading the client and server back and forth between send "Hello World" and 
recieve "Hello World" but the connection is being lost.... So 

A- the socket isn't being kept track of correctly
B- the program is freezing on the ServerHelper "socket.acept()" and is endlessly waiting for a client
C- the threading is wrong and bugging out the whole thing
D- some possible issue I am unaware of

