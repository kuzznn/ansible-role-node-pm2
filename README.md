```
- name: Install Node
  hosts: all
  become: yes
  roles:
    - node
  vars:
    version: 'v14.19.1'
    distro: 'linux-x64'
```