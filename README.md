ssh_config
==========

My Configuration for SSH

## Configuration

 Allow X11Forwarding
 Use Compression (blowfish)
 Use publickey authentication

## Public key Authentication

 Generate public key:

 ```
 ssh-keyget -t rsa
 ```

 Use *empty* passphrase

 Key is saved under ~/.ssh/

 Copy ~/.ssh/id_rsa.pub content into remote folder .ssh/authorized_keys

 Use the following command to add key to ssh-agent
 ```
 ssh-add 
 ```


