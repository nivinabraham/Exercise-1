# Exercise-1
StyleLabs Exercise 1: Basic Azure knowledge

Since this assesment is on Basic Azure Knowledge, i have chosen to use Azure builtin cloud bash shell to deploy ansible script

Azure Cloud Bash Configurations:
Add the subscription name while configuring Azure Cloud bash for the first time.

Ansible Playbook Deployment:
Step-1 : Upload the ansible-playbook.yml to the cloud shell
Step-2 : Move to the directory where ansible-playbook.yml file is placed.
Step-3 : run the command ansible-playbook ansible-playbook.yml
Step-4 : Sit back relax till the VMs are up and running

Note: I have chosen 2 Centos VM for this deployment.

Capture System Metrics:
Step-1 : SSH to the VM with username: azureuser and password: @zur3us3r
Step-2 : Upload iftop.sh and systemmetrics.sh to the VMs
Step-3 : I have used iftop to fetch the network usage and since this is a dependency for systemmetrics.sh to run, i have attached a script to install iftop.
Step-4 : run iftop.sh as sudo
Step-5 : run systemmetrics.sh to display the requested system metrics.
