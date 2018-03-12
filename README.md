A simple demo to show it's possible to orchestrate multiple openshfit-applier inventories without extending openshift-applier.

```
ansible-galaxy install -r requirement.yml --roles-path=roles"
ansible-playbook -i inventory/ run.yml
```
