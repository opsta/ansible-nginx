# Ansible Role: Nginx
Ansible role to install and configure Nginx


## Requirements

None.

## Role Variables



## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ansible-nginx

## How to run test ansible role
Use tox(virtualenv) and molecule(ansible role tester) \
Example run with tox
```
tox -e py37-ansible27 -- molecule test -s default
```

## License

MIT

## Author Information

Opsta (Thailand) Co.,Ltd.
