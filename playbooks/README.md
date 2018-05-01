## provision your laptop
```
ansible-playbook dev/site.yml -i '192.168.2.2,' -u josh -k -K
# -i: hosts to send commands to
# -u: username of account
# -k: password of account
# -K: sudo password if needed

ansible-playbook dev/site.yml -i '192.168.2.2,' -u vagrant
# if authorized by key and sudo can be executed without password
```
