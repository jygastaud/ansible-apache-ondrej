Apache Ondrej
=========

Simple role which set Ondrej Apache2 PPA for Debian/Ubuntu.

Requirements
------------

No requirements.

Role Variables
--------------

```
apache_repository: "ppa:ondrej/apache2"
```

Dependencies
------------

No dependencies.

However, we recommand to use that role combined with the excellent `geerlingguy.apache` role.

Combined with the geerlingguy role, you should be able to enable newest Apache modules as `http2`.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: jygastaud.apache-ondrej }

License
-------

MIT

Author Information
------------------

This role was created in 2017 by [Jean-Yves Gastaud](http://gastaud.io).
