# UDP_Drum_Machine
A simple drum machine that uses udp to share a metronome between multiple users.

Keanu Yokoyama 2019

This patch is intended to be used to test udp connection. 

If you have max, use the ".mxf" file or the ".maxpat" in conjucion with the shell tool. If you do not have max, download the application in the ".zip" file.

Requirements:
 1.git lfs is required to download the application (UDP_Drum_Machine.zip)
 2.the "shell" tool is needed to run the max patch, and can be found here https://github.com/jeremybernstein/shell/releases/tag/1.0b2

Instructions:

1.Connect to local network.
2.Choose network interface (en0 by default).
3.Click "start".

If you're having trouble connecting to another computer, try the multicast button, which casts over IP 225.225.225.225.

Online/Offline use can be toggled with the respective switch.

Udp connectivity sourced from user: source audio https://cycling74.com/author/58ed04e7285705c15ccfa694
