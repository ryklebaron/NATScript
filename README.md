# Turn your Linux computer into a router

This project is intended for students of Noorderpoort, School for IT in the Netherlands.

Students are required to install Proxmox on a server. Within our school, we only use eduroam Wi-Fi, which is perfect if you're only using a laptop or mobile phone.

When working with physical servers, I needed an internet connection for more than one reason. I created this script to turn your Ubuntu (Debian/Linux) desktop into a router. By default, it will try to use your system’s default gateway NIC as the WAN interface.

## No DHCP Server

Note that this script does not configure a DHCP server. You will need to set that up yourself or use static IP settings.

