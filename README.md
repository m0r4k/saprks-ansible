## USE YAML

* -K = ask for sudo
* [servers] = ServerSection in /etc/ansible/hosts

```
ansible-playbook [servers] install_rdate.yaml -K

#UPDATE DEBIAN/UBUNTU
ansible <server or [section]> -m apt -a "upgrade=yes update_cache=yes" -b

#ANY PROG START
ansible <server or [section]> -m shell -a "command"
```
