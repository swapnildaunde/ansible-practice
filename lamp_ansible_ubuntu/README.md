Steps to install LAMP on ubuntu Through Ansible

1. Install ansible on ubuntu machine by executing install_ansible_ubuntu.sh script.
2. Generate ssh key by cmd : ssh-keygen
3. Copy pub key to host machine by cmd :  ssh-copy-id root@host_public_id
4. Check if your hosts are ready by cmd : ansible -m ping all
5.  Execute playbook by cmd : ansible-playbook lamp.yml -K
