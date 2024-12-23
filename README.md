# home-lab
Ansible Playbook to configure the home lab

## Requirements

Install the required roles with:

```shell
ansible-galaxy install -r roles/requirements.yml
```

## Running the playbook

To run the playbook, use:

```shell
ansible-playbook -i inventory.yml site.yml
```
