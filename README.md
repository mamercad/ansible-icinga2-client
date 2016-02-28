mamercad.icinga2-client
=======================

Stands up an Icinga2 client on RHEL/CentOS

Warnings
--------

The role puts SELinux into permissive mode and disabled firewalld

Requirements
------------

None

Role Variables
--------------

See the example inventory below, as well as vars/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - icinga2
      roles:
        - mamercad.icinga2-client

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>

