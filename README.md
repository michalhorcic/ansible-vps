ansible-playbook 01-basic-install.yml --extra-vars "host_variable=testhibernal ansible_user=root" -i inventory.yml

# install python on dedicated machine
apt install python3 python3-pip
