# Ansible role: gitea
Git repos and project management

## Requirements
Only tested on Debian stable, for now.

## Role variables

# Dependencies
+ nginx
+ postgres

## Example Playbook

```
- hosts: gitea
  roles:
    - { role: ho-ansible.gitea }
```

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/
