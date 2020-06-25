# Sample Ansible code for driving ACI

2020.06.24

## Usage:

Rename inventory-sample.yaml to inventory.yaml and populate APIC credentials.

```bash
$ ansible-playbook -i inventory.yaml 01-tenant.yaml
```

## TODO:

- move tasks to role
- create standard policies (CDP, LLDP, LACP, etc)