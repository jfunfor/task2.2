Run this in directory where the playbook.yml is located

sudo ansible-playbook -i inventory.ini --ask-vault-pass playbook.yml

vault-pass:
changeme