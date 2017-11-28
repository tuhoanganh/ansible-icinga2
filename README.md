Please edit ansible.cfg file with following options:
- inventory  = /etc/ansible/playbook/inventory - Change to your inventory directory
- roles_path = /etc/ansible/roles	-	To your roles's dicrectory

Install single node:
- Edit and change variables in <directory_to_inventories>/staging/icinga2_single_inventory
- Run thi command:
ansible-playbook -i <directory_to_inventories>/staging/icinga2_single_inventory icinga2_single_node.yml

Install multi node:
- Edit and change variables in <directory_to_inventories>/staging/icinga2_single_inventory
- Run thi command:
ansible-playbook -i <directory_to_inventories>/staging/icinga2_multi_inventory icinga2_multi_node.yml
