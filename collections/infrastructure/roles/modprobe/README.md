# Modprobe

## Description

This role provides simply provides an interface to `**modprobe** Ansible module <https://docs.ansible.com/ansible/latest/collections/community/general/modprobe_module.html>`_ .

## Instructions

Set needed modprobes using a list:

```yaml
modprobe:
  - name: 8021q
    state: present
  - name: dummy
    state: present
    params: 'numdummies=2'
```

See `**modprobe** Ansible module page <https://docs.ansible.com/ansible/latest/collections/community/general/modprobe_module.html>`_
for the full list of available parameters.

## Changelog

**Please now update CHANGELOG file at repository root instead of adding logs in this file.
These logs bellow are only kept for archive.**

* 1.1.0: Update to pip Ansible. Benoit Leveugle <benoit.leveugle@gmail.com>
* 1.0.0: Role creation. Benoit Leveugle <benoit.leveugle@gmail.com>
