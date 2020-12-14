# Ansible - Reboot a Server 

Playbook to install apache and reboot the server

##Files

  - apache-reboot.yaml 
  - inventory.txt
  

# apache-reboot.yaml
Install apache & Reboot the server 
### 3 tasks
  -  Install apache service
  - Restart and enable the service
  - Copy files to document root
  - Reboot the server

## invenroty.txt
 - lists the hosts with ansible_user and ansible_ssh_private_key_file
