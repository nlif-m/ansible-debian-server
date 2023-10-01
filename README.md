# ansible-debian-server
A ansible playbook for default debian server

# Using
Install devsec.hardening ansible collection.

```shell
ansible-galaxy collection install devsec.hardening
```
Setup ansible inventory in `inventory.yml`.
Run ansible-playbook

```shell
ansible-playbook -i inventory.yml playbook.yml
```
