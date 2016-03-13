Ansible Docker
====================

To run Ansible run;

```
ansible-playbook -i hosts site.yml
```

Setup some enviroment varibles;

```
SSHKEY=$(cat ~/.ssh/id_rsa.pub)
```

Create a file called `do.yml` in the `group_vars`

```
do_api_token: "put-your-token-here"
```