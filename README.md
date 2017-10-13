ansible-role-chrony
================

[![Build Status](https://travis-ci.org/CSCfi/ansible-role-chrony.svg?branch=master)](https://travis-ci.org/CSCfi/ansible-role-chrony)

Role to install chrony ntp daemon in client mode.

Depends on ansible 2.0 (uses the package module)

This role has some changes and different defaults than the one it is forked from. The reason behind this is to make the role work for https://github.com/CSCfi/fgci-ansible

Role Variables
--------------

- chrony_ntp_servers: list of ntp servers, defaults to a set from pool.ntp.org.

Example Playbook
-------------------------

    - hosts: all
      roles:
        - ansible-role-chrony

License
-------

GPLv2

Author Information
------------------

- http://stillwell.me
- https://github.com/martbhell/
