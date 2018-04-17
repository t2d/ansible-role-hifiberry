ansible-role-hifiberry
======================

Configure [HiFiBerry](https://www.hifiberry.com/) on [Raspbian](https://www.raspberrypi.org/downloads/raspbian/).

Manual tutorial located at [HiFiBerry website](https://support.hifiberry.com/hc/en-us/articles/205377651-Configuring-Linux-4-x-or-higher).

Requirements
------------

Linux 4.x

Role Variables
--------------

```
hifiberry_model: hifiberry-dacplus
#hifiberry_model: hifiberry-dac
#hifiberry_model: hifiberry-amp
#hifiberry_model: hifiberry-digi
```

Example Playbook
----------------

    - hosts: pi
      roles:
         - { role: t2d.hifiberry, hifiberry_model: hifiberry-dac, tags: hifiberry }

License
-------

GPLv3

