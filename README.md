Gnome Settings
=========

Role for apply Gnome settings.

Example Playbook
----------------

    - hosts: desktop
      roles:
         - gnome-settings
      vars:
        settings:
          - { name: "/org/gnome/desktop/wm/preferences/num-workspaces", value: "4" }

License
-------

MIT