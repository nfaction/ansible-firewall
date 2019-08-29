# ansible-firewall

[![Build Status](https://travis-ci.org/nfaction/ansible-firewall.svg?branch=master)](https://travis-ci.org/nfaction/ansible-firewall)

Role to configure the host's firewall

## References

### Uncomplicated Firewall

* [Uncomplicated Firewall - ArchWiki](https://wiki.archlinux.org/index.php/Uncomplicated_Firewall)
* [How To Set Up a Firewall with UFW on Ubuntu 18.04 \| DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu-18-04)


### FirewallD

* [Firewalld - ArchWiki](https://wiki.archlinux.org/index.php/Firewalld)
* [Documentation - HowTo - Add a Service \| firewalld](https://firewalld.org/documentation/howto/add-a-service.html)
* [How To Set Up a Firewall Using FirewallD on CentOS 7 \| DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-using-firewalld-on-centos-7)

``` bash
# List all rules
firewall-cmd --list-all

# List services
firewall-cmd --list-services

# List all zones
firewall-cmd --list-all-zones

# List all ports
firewall-cmd --zone=public --list-ports

# Reload firewalld
firewall-cmd --reload
```
