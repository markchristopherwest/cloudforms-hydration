## Synopsis

cloudforms-hydration is a series of ansible playbooks aimed at reducing the cycle time in provisioning POC environments for field enablement.  the proverbial kewl-aide is consumed in a fashion to keep the automation coming.  also this is a good example of dog food by the sales team.

## Code Example

git clone, install stuff, pause, rinse & repeat

## Motivation

to sell more cloudforms

## Installation

install ansible from extra packages or epel:

$ yum install -y ansible

update the contents of your inventory file:

$ vi inventory.txt

launch the ansible playbook to begin the orchestration:

$ ansible site.yml -i inventory.txt


## API Reference

extra-vars can be implemented through the tower rest api

## Tests

launch an instance of cloudforms such as from fusion:

/Applications/VMware\ Fusion.app/Contents/Library/VMware\ OVF\ Tool/ovftool ~/Desktop/cfme-vsphere-5.7.0.17-1.x86_64.vsphere.ova ~/Desktop/Virtual\ Machines

## Contributors

this work would not be possible without my mentor at red hat aka mister cloudforms kevin morey aka rammrexx

## License

apache license 2.0
