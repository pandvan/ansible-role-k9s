# Ansible Role: k9s

This role installs [k9s](https://github.com/derailed/k9s) binary on your system.
Strongly inspired by [ansible-role-helm](https://github.com/geerlingguy/ansible-role-helm).


## Role Variables

Available variables are listed below, with their default values (see `defaults/main.yml`):
```yaml
k9s_version: '0.21.9'
k9s_platform: linux
k9s_arch: x86_64
k9s_bin_path: /usr/local/bin/k9s
```
