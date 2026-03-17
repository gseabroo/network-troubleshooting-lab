# network-troubleshooting-lab
I did a simulated IT Help Desk network troubleshooting lab using a Windows 10 VM with tools like ipconfig, ping, tracert and netstat to diagnose and resolve connectivity issues.


# Screenshots
## IP Configuration
### This step is usually the first action taken in network troubleshooting because it tells whether the issue is related to IP Assignment, gateway configuration, or DNS Resolution. In my lab, the 'ipconfig /all' command was used to examine the full network configuration of the system. 
! [IP Config](https://github.com/gseabroo/network-troubleshooting-lab/blob/main/ipconfig.png)

## Ping Test
### In my lab, the 'ping' command was used to test whether or not the system had connectivity to an external website (google.com). As you can see from the screensho, it helped determine that the system could communicate with the internet.
! [Ping](https://github.com/gseabroo/network-troubleshooting-lab/blob/main/ping.png)

## Tracert
### In my lab, the 'tracert' command was used to trace the route of google.com, which is what we used the 'ping' command for. It simulated the network path and helped to identify if there were any delays or interruptions between the source and the destination.
! [Tracert](https://github.com/gseabroo/network-troubleshooting-lab/blob/main/tracert.png)
