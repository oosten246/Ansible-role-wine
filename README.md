Ansible role wine
=================

Install Wine on Debian or Redhat based systems 

Requirements
------------

None

Role Variables
--------------
wine_branch can be staging, devel or stable

    wine_branch: staging

Dependencies
------------

None

Example Playbook
----------------

    - hosts: desktop
      become: true
      roles:
        - wine

License
-------

This software is available under the MIT license. See the LICENSE file for more info.

Author Information
------------------

oosten246
