# nsx_ansible_module_setup

Setup role for running [nsxansible](https://github.com/vmware/nsxansible)

## Operation check OS

* CentOS7

## Example Playbook

```yml
---
- name: NSX for vSphere Ansible Modules Setup
  hosts: server
  become: yes
  gather_facts: no
  roles:
    - nsx_ansible_module_setup
```

## ToDo

- [] Verification environment

## License

MIT

## Author Information

[sky-joker](https://github.com/sky-joker)
