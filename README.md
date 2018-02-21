apache-modules
=========

Ansible Modules for apache2, some written by other authors

Requirements
------------
a2enmod, a2dismod, a2ensite, a2dissite, a2enconf, a2disconf enabled on the server running the play

Role Variables
--------------

Dependencies
------------
None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - role: apache-modules

License
-------

GPLv2

Author Information
------------------

Role author: https://github.com/jxn
apache2_conf module author: Den Ivanov (see PR: https://github.com/ansible/ansible/pull/24370/files#diff-baf445298475bcbc44eb6955f9d467b6)
