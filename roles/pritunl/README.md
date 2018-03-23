Ansible role: Pritunl
=========

Installs Pritunl/OpenVPN server.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

+ EPEL repository
+ MongoDB

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: pritunl }

License
-------

GPL

Author Information
------------------

Nigel Marett <nigel@serverguru.co.uk>
