1- first step i create two virtual machines :
     - Ansible-Server with ip 192.168.182.130/24
     - Host-Server with ip 192.168.182.131/24
2- second step install ansible on Ansible-Server.
3- thirt step intiate secure connectio between two virtual machines by install the Ansible-server key on Host-server :
     - #ssh-keygen -t rsa 
     - #ssh-copy-id 192.168.182.131
4- step four identify the Host-server in hosts file ==> /etc/ansible/.
5- create the ansible playbook which contain all configration.
6- then push the configration to Host-Server by used : 
     - #ansible-playbook ansible-yaml-file.yml
     
 
