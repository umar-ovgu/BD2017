### Add user
```
sudo adduser neymar -u 2010
sudo adduser ronaldo -u 2016
```
### Add Group
```
sudo groupadd barca
sudo groupadd merengues
```
### Add user to Group
```
sudo usermod -a -G merengues neymar
```
### List password 
```
at /etc/passwd | grep neymar
neymar:x:2010:2010::/home/neymar:/bin/bash
cat /etc/passwd | grep ronaldo
ronaldo:x:2016:2016::/home/ronaldo:/bin/bash
```
### List group entires
```
cat /etc/group | grep barca
barca:x:2017:
cat /etc/group | grep merengues
merengues:x:2018:neymar

```
