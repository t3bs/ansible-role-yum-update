# Ansible Role: yum-update

Ansible role that upgrade all packages and REBOOTS SERVER if Kernel was upgraded

## Playbook Example

```yaml

- name: "Update all yum Packages"
  hosts: centos7
  become: true
  become_method: sudo

  roles:
      - ansible-role-yum-update

```

## Copyright

Copyright &copy; 

## License

Licensed under the Apache License 2.0. See LICENSE for details. All rights reserved.
