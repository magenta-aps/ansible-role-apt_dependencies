Apt install dependencies
=======================

An ansible role to install all apt dependencies.


Usage
-----

To utilize this role, add it to the `requirements.yml` file inside the ansible folder:

    - src: git+https://github.com/magenta-aps/ansible-role-apt_dependencies.git
      version: master
      name: apt_dependencies

Requirements
------------

Must be run against a `apt` capable system.

Example Playbook
----------------

    - hosts: all
      roles:
         - apt_dependencies
      vars:
         apt_dep_path: /vagrant/src/code/

License
-------

MPLv2

Author Information
------------------

dals83 - Danni Als
