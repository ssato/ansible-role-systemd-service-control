Role Name
=========

An example Ansible role to control systemd based service units.
It can the followings from ansible:

- Start/stop the systemd based servcie
- 

Requirements
------------

- The target service must be able to control using systemctl
- Ansible >= 2.5

Role Variables
--------------

see defaults/main.yml

Dependencies
------------

None

Example Playbook
----------------

see tests/test_start_stop.yml and tests/test_status.yml

License
-------

MIT

Author Information
------------------

Satoru SATOH <satoru.satoh@gmail.com>

.. vim:sw=2:ts=2:et:
