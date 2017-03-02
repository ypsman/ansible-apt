ansible-apt
===========
[![Build Status](https://travis-ci.org/ypsman/ansible-apt.svg?branch=master)](https://travis-ci.org/ypsman/ansible-apt)

running apt update, upgrade and autoremove in one Playbook

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.apt
