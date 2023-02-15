![Ansible Lint](https://github.com/johanneskastl/ansible-role-replace_kernel-default-base_with_kernel-default/workflows/Ansible%20Lint/badge.svg)

replace_kernel-default-base_with_kernel-default
=========

Replace kernel-default-base with kernel-default (as the base kernel is missing many modules you might need)


Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

Needs the `johanneskastl.reboot` role to trigger a reboot.

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.replace_kernel-default-base_with_kernel-default'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
