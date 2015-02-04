# Ansible role for Flexget

Ansible role for [Flexget](http://flexget.com/).

Note that [Flexget configuration](http://flexget.com/wiki/Configuration) has to be done manually.

Role Variables
--------------

You may want to override the `flexget_home`, set by default to `/srv/flexget`.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - ansible-role-flexget
```

License
-------

GPLv3

