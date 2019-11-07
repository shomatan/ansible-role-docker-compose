Ansible role: docker-compose
=========

Installs docker-compose.

Requirements
------------

None.

Role Variables
--------------

    docker_compose_bin_path: /usr/local/bin/docker-compose
    docker_compose_version: 1.24.1

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.docker-compose }

License
-------

MIT

Author Information
------------------

Shoma Nishitateno