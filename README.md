# Coll_NLA
Coll Marshall to support application to NLA

Folder contents:
NGINX Log Exercises: 2 x text files giving command, output/results and explanations/interpretations.
Puppet install exercise: 
  commands.txt: list of all the commands used in installation.
  20191204.x.log (x = 1,2,3): Output from this process. There are three log outputs because it was recorded on putty
            and I started an new log each new window: exit was done at one point to ensure group permissions received
            and started a new terminal session after "docker-compose up" because it acted as a log.
            I snipped some of the rpm output. Also the usual confused interpretation of vi screens is present.
  init.pp, motd.pp, site.pp: puppet files used.
  filestructure: the final tree of all files present.
  
I wasn't sure if there were specific puppet modules to install and couldnt see them specified. I was unfamiliar with 
puppet itself so I stole someone's motd helloworld project from https://puppet.com/docs/puppet/latest/quick_start_helloworld.html 
because it was a simple test of the process. It literally adds/replaces the /etc/motd file. 

This was done on a basic AWS EC2 Amazon Linux instance (uses a kernel based on RHEL). 
