Role Name
=========

This Role helps installing python dependencies used for
daily data-science work.

Requirements
------------

* Stouts.python

Example Playbook
----------------

The remote_user will be used as default for the toolkit installation.
You can override the parameter with `dst_user` if you want to.

    - hosts: servers
      remote_user: ubuntu
      roles:
         - { role: riethmayer.data-science-toolkit }

License
-------

MIT

Author Information
------------------

Jan Riethmayer, @riethmayer
bonusbox GmbH
