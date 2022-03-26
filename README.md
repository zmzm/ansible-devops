# Ansible devops

## Ping all servers from `ansible_hosts` file

```text
ansible -m ping all
```

## Connect to host via SSh

```text
ssh -vvv -i ~/aws/aws_keys/default_ec2.cer ec2-user@54.236.169.223
```

## Run commands for getting information about hosts

```text
ansible all -a "whoami" (inside "" could be any other command e.g. "python --version, uname, pwd, etc.")
```
