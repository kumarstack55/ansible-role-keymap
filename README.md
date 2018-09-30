ansible-role-keymap
===================

ansible role to change keymap setting.

Requirements
------------

* Ansible 2.2
* EL7

Role Variables
--------------

* keymap_vc_keymap (default: us)

Dependencies
------------

no dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: username.rolename, keymap_vc_keymap: jp }

License
-------

MIT

Author Information
------------------

kumarstack55@gmail.com
