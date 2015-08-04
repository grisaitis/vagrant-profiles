# vagrant-profiles

These folders contain basic examples of using vagrant to automatically provision virtual machines. 
- all install Ubuntu 14.04, trusty tahr
- all install java as part of the config script
  - in profiles 1 - 3, this is part of a ``bootstrap.sh`` file that includes some ``apt-get install`` commands
  - in profiles 4 - 6, I use someone else's script on GitHub: https://github.com/aglover/ubuntu-equip/blob/master/equip_java7_64.sh
  
My goal here was to learn how to provision a Spark cluster. This requires having java, scala, and then spark installed on a set of machines and configuring them to talk to each other. 
