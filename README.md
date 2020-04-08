# Vagrant Ubuntu 18.04 LTS base

Install vagrant from official downloads - https://www.vagrantup.com/downloads.html

Start the machine (user/pass: vagrant/vagrant):

    vagrant up

SSH into the machine:

    vagrant ssh
    
On any problems with provisioning run:

    vagrant provision --provision-with "install-software"

Stop machine with:

    vagrant halt

Reboot machine with:

    vagrant reload

Remove the machine from system:

    vagrant destroy

