# gvl-ansible-template
An ansible template for the GVL


## cancer.usegalaxy.org

Switch to the cloudman-boot folder and run:
```
ansible-playbook --ask-vault-pass -i ~/work/gvl-ansible-template/cancer.usegalaxy.org/inventory/hosts.ini -e @~/work/gvl-ansible-template/cancer.usegalaxy.org/group_vars/all/vars.yml -e @~/work/gvl-ansible-template/cancer.usegalaxy.org/group_vars/all/vault.yml playbook.yml
```

## template.usegalaxy.org

Switch to the cloudman-boot folder and run:
```
ansible-playbook --ask-vault-pass -i ~/work/gvl-ansible-template/template.usegalaxy.org/inventory/hosts.ini -e @~/work/gvl-ansible-template/template.usegalaxy.org/group_vars/all/vars.yml -e @~/work/gvl-ansible-template/template.usegalaxy.org/group_vars/all/vault.yml playbook.yml
```

## launch.usegalaxy.org

Switch to the cloudman-boot folder and run:
```
ansible-playbook --ask-vault-pass -i ~/work/gvl-ansible-template/launch.usegalaxy.org/inventory/hosts.ini -e @~/work/gvl-ansible-template/launch.usegalaxy.org/group_vars/all/vars.yml -e @~/work/gvl-ansible-template/launch.usegalaxy.org/group_vars/all/vault.yml playbook.yml
```
