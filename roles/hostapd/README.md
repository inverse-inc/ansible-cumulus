# Ansible hostapd role

Configure `hostapd` daemon on Cumulus Linux.

## Requirements

N/A

## Variables

See [defaults variables](defaults/main.yml)

## Examples

```
- name: configure Cumulus Linux
  hosts: cumulus
  collections:
  - inverse_inc.cumulus
  
  roles:
  - hostapd
```

If you use all defaults, `hostapd` will not start because you need to
configure at least one interface.
