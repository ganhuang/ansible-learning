## Usage scenarios
  Due to Ansible can't upgrade/downgrade Ansible itself, we need to identify if the installed ansible
  is suitable for our testing.
  The role is used to install suitable ansible on the slaves, and download openshift-ansible packages 
  on the slave for sequence tasks.

## Example Playbook

```
    - hosts: slave 
      roles:
         - openshift-ansible-slave  
```
