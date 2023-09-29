# ansible-role-rhsm_helper

**This ansible role is to help maintaing system registration to access.redhat.com or Satellite.**

TODO: If we run reg for a second time with different pool or different
environment, it will not change. This role should be able to update it.


## Installation

To install the role, create `requirements.yaml` with this content:

    - name: rhsm_helper
      src: https://github.com/jhutar/ansible-role-rhsm_helper.git
      version: origin/main

and then install the required depedencies for the role to work:

    ansible-galaxy collection install -r requirements.yml

Check `rhsm.yaml` or `satellite.yaml` for example on how to use the role in the playbook.


## Configuration

TODO


### Default variables

* `TODO` TODO


## References

1. TODO
