DATABASE Ansible role
==================

Role to manage DATABASE. Actually, this role is limited to a MySQL server, used for WordPress instances, and with the
creation of an admin user (able to create bases & tables for a WP instance).

Requirements
------------

No requirements

Role Variables
--------------

`database__install` For install only (default: False)
`database__configure` For configuration  (default: False)
`database__default_packages` Default packages to install

`database__conf.db_user` Admin user name (Default: "user")
`database__conf.db_password` Admin user password (Default: "pass")

Dependencies
------------

None

Example Playbooks
-----------------

License
-------

GPL v3

Author Information
------------------

François TOURDE
