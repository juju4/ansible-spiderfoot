[![Actions Status - Master](https://github.com/juju4/ansible-spiderfoot/workflows/AnsibleCI/badge.svg)](https://github.com/juju4/ansible-spiderfoot/actions?query=branch%3Amaster)
[![Actions Status - Devel](https://github.com/juju4/ansible-spiderfoot/workflows/AnsibleCI/badge.svg?branch=devel)](https://github.com/juju4/ansible-spiderfoot/actions?query=branch%3Adevel)

# spiderfoot ansible role

A simple ansible role to setup [Spiderfoot](https://github.com/smicallef/spiderfoot), OSINT tool.

## Requirements & Dependencies

### Ansible
It was tested on the following versions:
 * 2.17

### Operating systems

Tested on Ubuntu 24.04, 22.04

## Example Playbook

Just include this role in your list.
For example

```
- host: myhost
  roles:
    - juju4.spiderfoot
```

you probably want to review variables

## Variables

...

## Continuous integration

This role has github workflows for lint, galaxy release and molecule testing.

```
$ pip install molecule docker
$ molecule test
$ MOLECULE_DISTRO=ubuntu:24.04 molecule test --destroy=never
```


## Troubleshooting & Known issues

N/A

## License

BSD 2-clause
