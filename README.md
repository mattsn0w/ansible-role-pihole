# ansible-role-pihole
Deploy pihole to bricks.   

```
ansible-playbook --limit=brick4.co.slakin.net --become --ask-become-pass dns-ubuntu-server.yaml
ansible-playbook --limit=brick5.co.slakin.net --become --ask-become-pass dns-ubuntu-server.yaml
```
