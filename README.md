Role Name
=========

Hopla.cloud role for ansible to install a simple MariaDB server.

Requirements
------------

Ubuntu 18.04

Role Variables
--------------

user_name: "username"
user_email: "exemple@domain.com"
php_version "x.x"

Dependencies
------------

- hoplacloud.linux_update
- hoplacloud.linux_motd
- hoplacloud.fail2ban
- hoplacloud.postfix
- geerlingguy.mysql


Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.lamp

License
-------

GPLv3

Author Information
------------------

Joffrey Skandera for [hopla.cloud](https://hopla.cloud)
