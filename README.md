LukeT.ghost
========

This role will grab the latest release of ghost, push it to a system, provide it with basic configuration, and bring Ghost online .

Requirements
------------

None as of now. Next version will require EPEL and/or PPA for node packages.

Role Variables
--------------


| Name           | Description      |
|----------------|------------------|
| ghost_path | The full path where ghost is deployed  |
| ghost_port | What port ghost will listen on |
| ghost_ver | Currently set to latest, need to find further reference on their dl page for version drop in |
| ghost_url | The url that ghost should listen on, IP works well for dev |
| site_type | production, development callable NODE_ENV's in config.js |

Dependencies
------------

None.

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: LukeT.ghost }

License
-------

BSD

Author Information
------------------

No comment.
