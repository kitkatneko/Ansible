# Ansible Playbooks and building an Azure environment
Most of the ansible playbooks will create everything from vnet, subnet, rgs and vm all together. In larger environments, that not usually convenient to create a single book.

And so this is my attempts given my low understanding of Ansible to try to build new environments in Azure from almost scratch. This is how I am approaching a full 3 tier IaaS stack build with Ansible... PaaS would not be that far of and depending on what it is sone vnet integration is required.

* Foundations
  * VNET and Subnets
  * Resource Groups
  * common variables
  * server images
  * other infrastructure set up
* Roles in the environments
  * Web
  * Business App
  * DB
  * Management
  * Monitoring
  
## Foundations
### VNET and Subnets
I guess one of the first thing as a container for everything usually IaaS such as servers
