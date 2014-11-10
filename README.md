mysql
=====

This role installs and configures the MySQL.

Requirements
------------

* Debian

Role Variables
--------------

* `mysql_port`
* `mysql_root_password`

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: riaf.mysql, mysql_root_password: "s3cur1ty" }

License
-------

BSD

Author Information
------------------

Keisuke SATO
http://riaf.jp
