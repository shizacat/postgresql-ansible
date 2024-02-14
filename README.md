Postgresql - role for ansible
==========

Installs server postgresql.

There is such a thing: https://github.com/galaxyproject/ansible-postgresql

Requirements
------------

Support OS: CentOS7

Checked for Postgresql version: 9.6, 10.6, 11.1, 11.6, 11.7, 12.1

Ansible: 2.7.1

### Feature

- Supports the Cube extension with different dimension
- It is possible to specify the default settings for the cluster (locale)

Development
-----------

```bash
python3 -m venv .venv
. ./.venv/bin/activate
pip install ansible molecule molecule-plugins[docker]
```

Shorcuts:

```bash
molecule list

molecule create
molecule converge
molecule converge -s cube
molecule destroy
```

License
-------

MIT

Author Information
------------------

Alexey Matveev
