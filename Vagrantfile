# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.hostname = 'centos8'
  config.vm.box = 'sakeju/centos8-kernel5'
  config.vm.synced_folder ".", "/home/vagrant/vagrant_data"

  config.vm.provider "virtualbox" do |vb|
    vb.gui = true
    vb.memory = "1024"
  end
 
end
