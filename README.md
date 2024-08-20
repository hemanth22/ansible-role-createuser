Role Name: Create_user
=========

This role creates user and updates password.  

[![Build Status](https://travis-ci.org/hemanth22/ansible-role-createuser.svg?branch=master)](https://travis-ci.org/hemanth22/ansible-role-createuser)

Requirements
------------

passlib.
__How to install :__ install using command `pip install passlib` for password updation

Role Variables
--------------

Try exploring defaults/main.yml in the github to understand which variables can be override.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: hemanth22.create_user }

License
-------

GPLv3

Author Information
------------------

This role was created in 2019 by Hemanth BITRA.
