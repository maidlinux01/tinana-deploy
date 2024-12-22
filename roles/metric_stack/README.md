Role Name
=========

Deploy del stack de metricas que incluye:
 - Grafana
 - Prometheus
 - Nginx Proxy Manager.

Requirements
------------

Probado en
 - AlmaLinux 9.5
 - Debian 12

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Ejemplo de uso:
    - hosts: servers
      roles:
         - metric-stack

License
-------

MIT

Author Information
------------------

- Luis Enrique Morales Mendez "luis.moralesm@cyacomputer.com.mx"
