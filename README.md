DB Maintenance
==============

Backup databases and fetch the backups (PostgreSQL and/or MySQL).

Requirements
------------

...

Role Variables
--------------

    db_maintenance_backup_path: /tmp/backups
    
    db_maintenance_backup_download_path: /tmp
    
    db_maintenance_postgres_dbs: []
    
    db_maintenance_mysql_dbs: []

Dependencies
------------

No role dependencies.

Example Playbook
----------------

    ---
    
    - hosts: webservers
      gather_facts: yes
      sudo: yes
    
      roles:
        - ansible-db-maintenance
        
License
-------

MIT

Notes
-----

...
