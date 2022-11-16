# jenkins-playbook-for-ubuntu 22.04
ansible-playbook java11.yml -kK

ansible-playbook -i hosts java11.yml       for all host

ansible_ssh_private_key_file=/home/server/.ssh/id_rsa

For each host ansible-playbook playbook.yml -l server1 -u root
