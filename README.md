pcopfer.nginx-default
=====================

A role to add a default Page to nginx Server with Https.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

- ``nginx_sites_path: /etc/nginx/sites``
- ``nginx_locations_path: /etc/nginx/sites-enabled``
- ``nginx_default_servername: "{{ ansible_fqdn }}"``
- ``nginx_default_ssl: yes``

Dependencies
------------

- ``pcopfer.nginx-default``: https://github.com/rixx/ansible-nginx-base

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: pcopfer.nginx-default

License
-------

BSD

Author Information
------------------

pcopfer <christian-platz at pcopfer.de>
