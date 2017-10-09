# ansible-docker
Ansible to start container Ubuntu SSHD, then retrieve IP address and execute action to the container. 


Usage:

- Clone repositpory. 

- Ensure you have the Docker Precom SSHD image (built from ubuntu:16.04)

- If not present, install Ansible 2.4 : 

sudo apt-get install python-pip
sudo pip install ansible==2.4

ansible-playbook -i ./hosts ./playbook.yml
