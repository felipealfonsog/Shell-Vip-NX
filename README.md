# Shell Vip Utility written in C for *NX Systems

Simple: Vip shell to avoid usage of sudo

#

Crafted by Software Engr. / Developer Felipe Alfonso González - felipe@nodeio.us

#instructions

 | gunzip vip.c.gz
 
 | gcc -o vip vip.c (compilation)
 
 | su
 
 | vi /etc/group (nuevo grupo, ej.: staff:x:100:user)
 
 | mv vip /usr/bin/
 
 | exit
 
 | vip
 

