cgusers
=========

This role allows you to manager CPU and memory settings for transient sessions via cgroups. In other words, user sessions.

Requirements
------------

- Fedora 30 or higher
- RHEL 8.0 or higher

Transient units used to work on older RHEL/Fedora versions but got broken during the RHEL 7 lifecycle. Compatibility was restored with RHEL 8. If you're running very old RHEL 7, this role might work but you're going to be dealing with bugs and security holes that should be closed with patches.

Role Variables
--------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPL v 3

Author Information
------------------

original author Marc Richter, mrichter@redhat.com

