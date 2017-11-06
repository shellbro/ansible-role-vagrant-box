vagrant-box
===========

[![Build Status](https://travis-ci.org/shellbro/ansible-role-vagrant-box.svg?branch=master)](https://travis-ci.org/shellbro/ansible-role-vagrant-box)

Ansible role that configures CentOS 7 to meet Vagrant box requirements.
When packer is used to build images, this role is a convenient way to provision operating system.

Requirements
------------

Ansible version >= 2.3.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - shellbro.vagrant-box

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
