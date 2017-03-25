Ansible Docker for Ubuntu
==

Installs Docker on Ubuntu 16.04 (may work on other versions, but not tested)

**Example Play**:
```
---
- hosts: all
  roles: ansible-docker
```

Requirements
------------
* Ubuntu 16.04 comes with python3 by default.  You will either need to specify the path to the python executable, or install python 2.7.x

Dependencies
------------
None
