# Playbook - [Logging](.)

Developement environment

```sh
ansible-playbook -i inventories/dev/ -e @vaults/dev.yaml --vault-password-file=.dev_ansible_vault_pass playbooks/logging/logging.yaml
```

Production environment

```sh
ansible-playbook -i inventories/prod/ -e @vaults/prod.yaml --vault-password-file=.prod_ansible_vault_pass playbooks/logging/logging.yaml
```

## Roles

### [1: Install](./install/)
