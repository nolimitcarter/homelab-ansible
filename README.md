## homelab-ansible

Ansible code to configure and maintain my lab. 

### Usage 

Run baseline against all hosts 
`anisble-playbook playbooks/site.yml`

Run against one host
`ansible-playbook playbooks/site.yml --limit linux-target`

`ansible-playbook playbooks/site.yml --check`

### Structure

* `inventory/` - host and group definitions
* `group_vars/` - variables shared across host groups
* `host_vars/` - variables for individual hosts
* `playbooks/` - top-level orchestration
* `roles/` - reusable units


