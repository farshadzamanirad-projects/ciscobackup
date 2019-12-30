# ciscobackup 
Ansible ciscobackup simple and fun which will fetch running-config !

Usage : 
```ansible-playbook ciscobackup.yaml -i ciscoinventory.yaml```

Don't forget to install sshpass and if you got problem using ssh to cisco device due to Cipher please add :

```Ciphers aes256-ctr,aes128-cbc,3des-cbc,aes192-cbc,aes256-cbc```

to your `/etc/ssh/sshd_config`

... Have fun!
