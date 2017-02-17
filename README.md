Ioncube
=========

This role will download  the Ioncube loaders 64Bits into a specified folder.

By default, it will decompress the package into `/opt` but it can be changed using the ioncube_path variable.

Role Variables
--------------
`ioncube_path: /opt` Folder where you want to install ioncube


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    ---
    - name: Install ioncube
      hosts: all
      become: yes
      vars:
        ioncube_path: /opt
      roles:
        - { role: cristian04.ioncube }

License
-------

BSD

Author Information
------------------

[Cristian Russo](mailto:cristian.russo@clearpoint.co.nz)