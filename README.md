# Ansible Role to Install LAMP Stack on Amazon Linux 2

The role can be used to install a fully featured LAMP stack on Amazon Linux and deploy a Wordpress over it.

Features
------------

- Fully configurable and compatible with AWS.
- Flexible and feature rich with easy customization of roles.
- Can be modified to support additional modules.
- Can be used to create a standalone LAMP stack or deploy applications over the current LAMP stack.

Role Variables
--------------

The variables can be edited from /vars/main.yml as per the requirements.

- domain
- httpd_port
- httpd_owner
- httpd_group
- mysql_root
- mysql_user
- mysql_password
- mysql_database
