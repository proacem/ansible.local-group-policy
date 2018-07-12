# Ansible Role: local-group-policy

[![Build Status](https://travis-ci.org/sbaerlocher/ansible.local-group-policy.svg?branch=master)](https://travis-ci.org/sbaerlocher/ansible.local-group-policy) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-local-group-policy-blue.svg)](https://galaxy.ansible.com/sbaerlocher/local_group_policy)

## Description

Copies the Local Group Policy from a Git Repostory to a Windows system.

## Installation

```bash
ansible-galaxy install sbaerlocher.local-group-policy
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| local_group_policy_repo | `https://github.com/sbaerlocher/windows.local-group-policy.git` | |
| local_group_policy_directory | C:\Windows\System32 | |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.local-group-policy
```

## Changelog

### 1.0.0

* inital commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher