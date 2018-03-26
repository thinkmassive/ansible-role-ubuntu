Ubuntu
======

Common setup for Ubuntu servers.

Requirements
------------

Target hosts should have python installed.

Role Variables
--------------

  - `common_packages` - list of packages to install on each host

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: thinkmassive.ubuntu, common_packages: [ 'vim', 'git' ] }

License
-------

Apache 2

Author Information
------------------

Alexander Miller alex@thinkmassive.org
