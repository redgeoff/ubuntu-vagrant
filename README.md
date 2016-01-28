# ubuntu-vagrant

A quick way to get an updated ubuntu VM set up


Install Vagrant, VirtualBox and git
---

    http://www.vagrantup.com
    https://www.virtualbox.org (don't worry about setting up any VMs as the steps below will cover this)
    http://git-scm.com


Set up
---

    Edit /etc/hosts locally and add `192.168.50.11 ubuntu.dev`
    $ git clone https://github.com/redgeoff/ubuntu-vagrant.git
    $ cd ubuntu-vagrant
    $ vagrant up
    $ vagrant ssh
