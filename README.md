# helloworld
practice

##
1. generate new ssh key 
```
$ ssh-keygen -t ed25519 -C "your_email@example.com"
$ open ~/.ssh/config
$ touch ~/.ssh/config
```

2. 
```
Host *
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_ed25519
```