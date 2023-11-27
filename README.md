# You can install roles and collections from the same requirements files
---
roles:
  # Install a role from Ansible Galaxy.
  - name: geerlingguy.java
    version: "1.9.6" # note that ranges are not supported for roles

collections:
  # Install a collection from Ansible Galaxy.
  - name: community.general
    version: ">=7.0.0"
    source: https://galaxy.ansible.com
