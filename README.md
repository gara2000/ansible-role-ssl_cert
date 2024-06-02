SSL-CERT
=========

Deploy ssl certification

Requirements
------------

- Runs on Ubuntu
- Requires nginx website to be configured

Role Variables
--------------

- domain: The domain name
- email: The email address for important account notifications 

Dependencies
------------

- gara2000.nginx role version v1.2.0

Example Playbook
----------------

```yaml
- hosts: servers
  become: yes
  roles:
      - gara2000.nginx
      - gara2000.ssl-cert
```

License
-------

MIT
