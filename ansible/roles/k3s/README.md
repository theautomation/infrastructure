Role Name
=========

Install k3s bare

Requirements
------------


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------
```
ansible-playbook k3s_rolling_update_nodes.yaml
```
```
sudo ansible-playbook --ask-vault-pass -kK k3s_install_cluster_bare.yaml
```
```
sudo ansible-playbook --ask-vault-pass -kK k3s_install_cluster_minimal.yaml
```

Stop nodes
```
sudo ansible-playbook -k k3s_stop_all_nodes.yaml
```

Start nodes
```
sudo ansible-playbook -k k3s_start_all_nodes.yaml
```

Rolling update nodes
```
ansible-playbook k3s_rolling_update_nodes.yaml
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
