# unixChat

To run the program, open a shell for the server, and 1 shell per desired client.

To compile the server, type: gcc chatserverC.c -o chatserverC -pthread

and to run, type: ./chatserverC

To compile the client (which needs a running server), type: gcc chatclientE.c -o chatclientE -pthread

and to run, type: ./chatclientE \<server's local IP address\>

If you start more than one client, you can chat between terminals on your local network.
