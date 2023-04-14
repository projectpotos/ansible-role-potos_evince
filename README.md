
# Ansible Role - potos\_Evince

Role to install Evince on Potos.

[![Test](https://github.com/projectpotos/ansible-role-potos_template/actions/workflows/test.yml/badge.svg)](https://github.com/projectpotos/ansible-role-potos_template/actions/workflows/test.yml)

## Example Playbook

As this role is tested via Molecule one can use [that
playbook](./molecule/default/converge.yml) as a starting point:

```yaml
---

- name: Converge
  hosts: all
  gather_facts: yes
  tasks:
    - name: run role
      ansible.builtin.include_role:
        name: 'ansible-role-potos_evince'
```

## Requirements

N/A

## License

See [LICENSE](./LICENSE)

## Author Information

- [Project Potos](https://github.com/projectpotos)
- [Jocomol](https://github.com/Jocomol)
