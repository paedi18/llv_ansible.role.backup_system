
# Basis Backup Rolle
Eine Rolle um standardisierte und konsistente Applikations Backups zu ermöglichen

## WHY
* Mariadb (LLV Standard)
* Rundeck (LLV Standard)
* Guacamole (LLV Standard)
* FreeIPA (LLV Standard)
* Kubernetes(K3S, (LLV Standard))
* AWX(K3S, (LLV Standard))
* /usr/local/sbin/backup.sh (if file exists)

## HOW IT WORKS
* Find applications by searching for well known service names
* change status is always 0 if host has no backup
* change status is always >0 if host has backup


Role Variables
--------------

Variables are speaking or documented in defaults/main.yml   



## Dependencies

This Ansible Role has no dependencies to other Ansible Roles

License
-------
https://opensource.org/licenses/GPL-3.0    
Copyright (c) Chris Ruettimann <chris@bitbull.ch>

