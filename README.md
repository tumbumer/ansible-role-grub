# tumbumer.grub

Manage GRUB configuration.

## Requirements

None.

## Role Variables

* `tumbumer_grub_timeout`
* `tumbumer_grub_cmdline_linux_default`

All variables are optional.

## Dependencies

None.

## Example Playbook

```yaml
---
- hosts: all
  vars:
  - tumbumer_grub_timeout: 0
  - tumbumer_grub_cmdline_linux_default: ipv6.disable=1 elevator=noop
  roles:
  - tumbumer.grub
```

## License

Apache-2.0

## Author Information

Denis Dvoretskov aka tumbumer <denis@tumbum.com>
