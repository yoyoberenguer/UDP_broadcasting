# UDP_broadcasting
Video and sound broadcasting trough UDP/TCP sockets

Play a demo in real time and send video packets through a socket using UDP protocol on localhost. 
The animation display on the small window is the video rebuild from the UDP packets.
You can exit the demonstration by pressing ESC key after clicking inside the window.

The synchronisation between the client/server is achieve using threading conditions and threading events.
Every packets are checked for checksum error and synchronisation issue. 

To start the demo
```
C:\>UDP_Broadcast -a 127.0.0.1 -p 59000 

```
To run the program from source you will need the following libraries installed on your system

1) lz4.frame
2) ctypes
3) pygame
