# ansible-roles-sample
Sample repo for demonstrating the use of ansible roles

### Running the playbook and creating the roles
#### Running / Deploying the playbooks
```
ansible-playbook apache-install.yml -i inventory.txt --ask-become-pass
```
Enter your remote machine sudo password to continue...

#### Creating roles using ansible-galaxy as follows
For java-check role
```
ansible-galaxy init java-check --offline
```
For install-apache role
```
ansible-galaxy init install-apache --offline
```
For start-apache role
```
ansible-galaxy init start-apache --offline
```

Note: --offline option is used to create content locally not to download from internet. if we do not specify, it will be downloaded from internet.

##### ________________________________________________ END ___________________________________________________