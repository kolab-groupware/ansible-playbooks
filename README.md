## Ansible Playbooks for Kolab 16 on Debian Jessie

## Usage


```yaml
---
- hosts: kolab
  become: yes
  gather_facts: yes
  roles:
    - kolab
```


