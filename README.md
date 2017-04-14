slacktee for Ansible
=================

A role for installing [slacktee](https://github.com/course-hero/slacktee)


Usage
-----

Clone this repo into your roles directory:

    $ git clone https://github.com/gfolga/ansible-slacktee.git roles/slacktee

And add it to your play's roles:

    - hosts: ...
      vars:
        - webhook_url: https://...
        - channel: ...
        - ...
      roles:
        - slacktee
        - ...


Changelog
---------

### 0.1

Initial version.
