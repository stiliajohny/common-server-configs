Role Name
=========

This role is created to copy the MOTD as well as some BashRC and ssh banners

Requirements
------------

To test the role with the included molecule test ensure you have the following installed:
- molecule==3.2.0
- molecule-vagrant
- python-vagrant
- vagrant
- ansible

Role Variables
--------------

Check the defaults for all necessary variables to be adjusted

Dependencies
------------

N/A

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - { role: server_banner_prompts }
```

License
-------

GPL3

Author Information
------------------

John Stilia   - [@john_stilia](https://twitter.com/john_stilia) - stilia.johny@gmail.com
