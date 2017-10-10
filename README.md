# Ansible Role: MariaDB

Installs MariaDB 10.1  on new cloud instances or upgrades to MariaDB 10.1 on Interworx instances. Only usable with CentOS 7.
 
## Role Variables

See `defaults/main.yml`.


## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-mariadb.git
      name: nexcess.mariadb

## Example Playbook

    - hosts: php_hosts
      roles:
        - nexcess.mariadb

## License

MIT