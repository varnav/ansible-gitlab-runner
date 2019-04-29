[![Build Status](https://travis-ci.org/varnav/ansible-gitlab-runner.svg?branch=master)](https://travis-ci.org/varnav/ansible-gitlab-runner)


How to Install
--------------

`ansible-galaxy install varnav.ansible_gitlab_runner`


Example Playbook
----------------

```
---
- hosts: mailservers
  roles:
       - varnav.ansible_gitlab_runner
```

How to run
----------

`ansible-playbook opendkim.yml --limit mailservers`
