# welcome to the Davis Catylist center cybersecurity DHCP github project!
This repository contains the configuration files for setting up dnsmasq with our settings. 
If you want to use our settings install DNSmasq and input the following commands into your command line:

```shell
git clone https://github.com/evilTachyMeter/catalystDHCP
cd catylistDHCP
cp dnsmasq.conf /etc/
cp -r dnsmasq.d /etc/
```
make sure to read the files and to edit ip addresses and internet interfaces

populate the hosts file with the ip addresses and hosts of static ip servers

the following link is helpful for the setup, even if it is meant for arch linux, it still applies to
any linux distro

[https://wiki.archlinux.org/title/dnsmasq]
