Role Name
=========

ansible-ntp

Requirements
------------

- system: Centos 7.x

Role Variables
--------------

ntp_server: default 127.0.0.1

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: ansible-ntp, ntp_server: "0.cn.pool.ntp.org" }

License
-------

BSD

Author Information
------------------

by weimeng
