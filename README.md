# PFNASS-Ansible

# To run pf-network-ansible from root project directory

`ansible-playbook -u root -i pf-network-ansible/inventory.yml -p pf-network-ansible/playbook.yml`

# To run pfnass-ansible from root project directory

`ansible-playbook -u root -i pfnass-ansible/inventory.yml pfnass-ansible/playbook.yml`

# Optionally, can also run only specific tags, or multiple tags

`ansible-playbook -i pfnass-ansible/inventory pfnass-ansible/playbook.yml --tags "insert tag here"`
