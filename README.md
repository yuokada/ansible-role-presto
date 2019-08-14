Role Name
=========

Ansible role to install prestodb/presto in CentOS.

[![Build Status](https://travis-ci.com/yuokada/ansible-role-presto.svg?branch=master)](https://travis-ci.com/yuokada/ansible-role-presto)
[![Platform](http://img.shields.io/badge/platform-centos-932279.svg?style=flat)](#)

Requirements
------------
TBD
<!--
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.
-->

Role Variables
--------------
TBD
<!--
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.
-->

Dependencies
------------
- [Ansible Galaxy](https://galaxy.ansible.com/lean_delivery/java)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: presto-server
      roles:
        - {role: presto, presto_client_install: false}

----
    - hosts: presto-client
      roles:
        - {role: presto, presto_server_install: false, presto_client_install: true}




License
-------

BSD
