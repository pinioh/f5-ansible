Migration of bigip virtual server with Ansible Playbook.

1. Edit the hosts file with source and destination systems
2. Edit the variables with the virtual server name

[bigip_src]
bigip1.pini-ohayon.lab

[bigip_src:vars]
bigip_virt_migrate=virt_NAME

[bigip_dst]
bigip2.pini-ohayon.lab

[bigip_dst:vars]
bigip_virt_migrate=virt_NAME

