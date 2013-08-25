# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "precise64"
  config.vm.box_url = "http://files.vagrantup.com/precise64.box"
  config.vm.network :private_network, ip: "192.168.111.222"
  # config.vm.network :public_network
  #config.vm.provision :ansible do |ansible|
  #  ansible.verbose = true
  #  ansible.playbook = "site.yml"
  #  ansible.inventory_file = "vagrant_hosts"
  #end
end
