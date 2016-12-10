Role Name
=========

[![Build Status](https://travis-ci.org/patrick-hill/ansible-role-packer.svg?branch=master)](https://travis-ci.org/patrick-hill/ansible-role-packer)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-patrick--hill.packer-blue.svg)](https://galaxy.ansible.com/patrick-hill/packer)


Installs [Packer](https://www.packer.io/) on Debian based OS


Requirements
------------

Ansible 2.0+

Role Variables
--------------

    packer_version: 0.12.0
"packer_version: 0.12.0" is the desired version, tested are: `0.9.0` & `0.12.0`

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: development-machines
      roles:
        - { role: patrick-hill.packer}

License
-------

BSD

Author Information
------------------

Role written in 2016 by [Patrick Hill](http://www.HillsPCWorld.com) 
