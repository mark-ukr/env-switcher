# fe-ansible

Simple script for automatic management of `/etc/hosts` and nginx-related symbolic links.

## Installation

1. Clone this repository to ~/git-repos/fe-ansible
2. [Install Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html)
<details>
  <summary>Installation in Ubuntu</summary>
  
```
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```
</details>
  

## Usage:

```
#dev:
./set-my-env-to dev

#gang:
./set-my-env-to gang

#int:
./set-my-env-to int

#demo:
./set-my-env-to demo
```
