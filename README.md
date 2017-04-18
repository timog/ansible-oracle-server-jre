Role Name
=========

Download, copy and extract the Oracle Java JRE or Oracle Java Server JRE from the standalone .tar.gz file.

Requirements
------------

TODO

Role Variables
--------------

TODO

Dependencies
------------

none

Example Playbook
----------------

     - hosts: servers
       remote_user: root
       roles:
         - role: ansible-oracle-server-jre
           oracle_server_jre_flavour: jre
           debug: true
       become: yes

License
-------

MIT

Author Information
------------------

Timo Goiss
