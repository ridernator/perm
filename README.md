# perm
**Bash script to verbosely print out the permissions of files (Including SUID, SGID and sticky bit)**

**Usage :** perm files

**Example :**
```
[root@alfie perm]# perm /usr/bin/write /usr/bin/vim

File : /usr/bin/write
Permissions : -rwxr-sr-x
The user root has read permissions on this file
The user root has write permissions on this file
The user root has execute permissions on this file
Users in the group tty have read permissions on this file
Users in the group tty do not have write permissions on this file
Users in the group tty have execute permissions on this file
Other users have read permissions on this file
Other users do not have write permissions on this file
Other users have execute permissions on this file
Users executing this file will do so with root group's privileges

File : /usr/bin/vim
Permissions : -rwxr-xr-x
The user root has read permissions on this file
The user root has write permissions on this file
The user root has execute permissions on this file
Users in the group root have read permissions on this file
Users in the group root do not have write permissions on this file
Users in the group root have execute permissions on this file
Other users have read permissions on this file
Other users do not have write permissions on this file
Other users have execute permissions on this file
```
