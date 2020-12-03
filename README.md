tenantcloud.auditbeat
=========

Ansible role for install and setup auditbeat. This role include in default terraform scenario for auto-deploy new server.

Requirements
------------

Role Variables
--------------

elk_url: localhost
elk_username: username
elk_password: password

Dependencies
------------

Example Playbook
----------------

```yaml
  - hosts: localhost
    become: true
    vars:
      ansible_user: ubuntu
      elk_url: localhost
      elk_username: username
      elk_password: password
    roles:
      - tenantcloud.auditbeat
```

License
-------

BSD

Author Information
------------------

TenantCloud DevOps Team
