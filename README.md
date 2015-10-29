# Network policy lab

A POX controller application based using the Bellman-Ford algorithm to find shortest path in a network.
The application will always try to use the least used nodes (based on packet counts) in the network.
It listen to link events, if a link goes down the controller will delete rules on the switches which share the link.

# Run the script
- Install POX and Mininet
- Add script to the ext-folder in pox
- Start up a mininet network with connection to pox controller
- Run application by: ./pox.py ext.Lab5
