Role Name
=========

Ansible role which installs / configures vsftp


Role Variables
--------------

```
vsftpd_anonymous_enable: "NO"
vsftpd_local_enable: "YES"
vsftpd_write_enable: "YES"
vsftpd_listen: "YES"
```


Example Playbook
----------------

```
    - hosts: servers
      become: yes
      roles:
         - vsftpd

```
