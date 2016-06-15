# create-dev-vm
This repo create a development VM using vagrant.
Additionally software is installed via ansible.
Also the repositories of RapidPm will be cloned.

##Prerequsites
* Vagrant 
* VirtualBox 
* Ansible

## Usage

###Cloning the repo
 Beacuse this repo usesgit submodules for ansible roles you have to check out this repo recursive.
`git clone --recursive https://github.com/merodwin/create-dev-vm.git`

### Booting and installing the VM

Go to the top folder of this repo.
and then `vagrant up`
This will install the VM.

### Loging in to the VM
Open the VM withing Virtualbox with the user `vagrant` and the password `vagrant` 

## Whats in it
When the VM is installed you have the following software installed

| Software | version | path |
|--|--|--|
| IntelliJ Ultimate Edition| 2016.1 | /opt |
| Maven | 3.3.9 | /opt |
| Vagrant |1.8.1 |/opt|
| Oracle JDK | 8_92 b14 | /opt | 


 
