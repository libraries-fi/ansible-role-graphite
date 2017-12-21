kifi.graphite
=============

Installs and configures Graphite on Debian Stretch systems.

Requirements
------------

None.

Role Variables
--------------

 * graphite_port: HTTP port for Graphite Web 
 * graphite_vhost_ip: IP address to listen requests from
 * graphite_timezone: timezone to use for Graphite

Dependencies
------------

 * ajsalminen.apt_source

Example Playbook
----------------

```
- hosts: graphite
  roles:
    - role: kifi.graphite
```

License
-------

MIT

Author Information
------------------

Libraries.fi
