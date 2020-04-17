# ansible_ntpd
Ansible Playbook, allows to deploy ntpd locally and set specific time server


## Requirements:

- Ansible must be installed on your machine

- Running the playbook on Debian disribution ( tested on Ubuntu 18.04 ) 


## Getting Started:

This paybook allows to install or to update ntpd to the local machine 


* Installation:

1. Download the repo or use git to clone in your home directory:

git clone https://github.com/ghassencherni/ansible_ntpd.git


2. Change directory:

cd ansible_ntpd


3. Run the playbook by taping this command: 

ansible-playbook ansible_ntpd.yml -i hosts.yml


## How to test the deploy:

- Check that the configuration file /etc/ntp.conf contains the added time server,

- check that ntp daemon is running : service ntp status


## Author Information

This script  was created by [Ghassen CHARNI](https://github.com/ghassencherni/)

