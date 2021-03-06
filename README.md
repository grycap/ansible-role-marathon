[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![CI](https://github.com/grycap/ansible-role-marathon/actions/workflows/main.yaml/badge.svg)](https://github.com/grycap/ansible-role-marathon/actions/workflows/main.yaml)

Marathon Role
=============

Install Marathon in a Mesos cluster (recipe for EC3). The Marathon current version installed is Version 1.3.6.

Example Playbook
----------------
```
  - hosts: server
  roles:
  - { role: 'grycap.marathon'}
```
```
  - hosts: client
  roles:
  - { role: 'grycap.marathon'}
```

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
