# Docker development scripts
With respository contains a number of bash script which make it possible to run a local development envoirment for docker. 
It make use of rancher a opensource management system for docker stack or swarm. 

##Usage
run the start.sh it will create the virtual machine. a master and a slave. And it wil set the nessecary configuration so that everyting will work.
when you shutdown your pc you kan reenable them with the same script. It wil also check your /etc/hosts file and will update the ip adresses
acordely

it also possible to force create a new client server with the createRancherClient.sh script

## requiremnts
 - unix shell commands. I should be working with git bash. but it will definetly work with cygwin.
 - Docker toolbox. Vbox needs to be installed is the nd6 drivers (which is the defaults settings)
 

##Warnings
I haven't fully tested the scripts. I use them for my own development enviorment at the moment so there kind of stable and I wil keep
updating them when I discover bugs. 

