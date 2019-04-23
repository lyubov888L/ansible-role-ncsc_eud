ncsc-eud
========

A role to apply [NCSC End User Device hardening guidelines](https://www.ncsc.gov.uk/collection/end-user-device-security?curPage=/collection/end-user-device-security/platform-specific-guidance)
for Ubuntu 18.04

This is implemented with the exception of:

* VPN (not implemented)
* TPM (partially implemented)
* External Interface Protection (partially implemented)

Requirements
------------

Repositories should already be configured and up-to-date

Role Variables
--------------

Please see defaults/main.yml, variables are self-explanatory

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ncsc-eud-ubuntu, x: 42 }

License
-------

GPLv3

Testing
-------

Require for testing:
* Vagrant
* Python 3
* Pipenv

Author Information
------------------

* [Brett Delle Grazie](https://github.com/bdellegrazie/)
