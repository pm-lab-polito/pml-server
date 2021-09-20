# setting up the server to git this repo

Create a github user. See secrets.md for credentials.

ssh to pmlab server.

``` bash
$ sudo su
# cd /home/root/.ssh
# ssh-keygen -t ed25519 -C "pm-lab@polito.it"
```

save as id_ed25519_github

output the .pub (see secrets)

add to github.com ssh keys

clone this repo

``` bash
# cd /srv
# git clone git@github.com:pm-lab-polito/pml-server.git
```
