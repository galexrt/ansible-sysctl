ansible-sysctl
==============

A simple Ansible role for setting sysctl vars.

Requirements
------------

No special requirements.

Role Variables
--------------

```
sysctl:
  - name: test
    value: 100
    state:
    ignoreerrors: no # allows for manual setting it
```

Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
- hosts: servers
  roles:
    - { role: galexrt.sysctl, sysctl: [{ name: test, value: 100 }] }
```

License
-------

MIT

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
