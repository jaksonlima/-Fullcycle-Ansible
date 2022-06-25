```
ansible -i hosts all -m ping
```

```
ansible -i hosts node1 -m ping
```

```
ansible -i hosts all -m apt -a "update_cache=yes name=git state=present or absent"
```

```
ansible -i hosts all -m git -a "repo=https://github.com/jaksonlima/terraform"
```

```
ansible -i hosts all -m setup
```

```
ansible -i hosts node2 -m shell -a "ls -la"
```

```
ssh-keygen
```

```
ssh-copy-id root@node1
```

```
ssh-copy-id root@node2
```

```
ssh root@node1 ou ssh root@node2
```
