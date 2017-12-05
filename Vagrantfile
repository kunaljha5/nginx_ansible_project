# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "lb02" do |lb02|
    lb02.vm.box = "ubuntu/trusty64"
    lb02.vm.hostname = "lb02"
    lb02.vm.network :private_network, ip: "10.11.12.53"
  end

  config.vm.define "web03" do |web03|
    web03.vm.box = "ubuntu/trusty64"
    web03.vm.hostname = "web03"
    web03.vm.network :private_network, ip: "10.11.12.54"
  end

  config.vm.define "web04" do |web04|
    web04.vm.box = "ubuntu/trusty64"
    web04.vm.hostname = "web04"
    web04.vm.network :private_network, ip: "10.11.12.55"
  end

  config.vm.define "web01" do |web01|
    web01.vm.box = "ubuntu/trusty64"
    web01.vm.hostname = "web01"
    web01.vm.network :private_network, ip: "10.11.12.51"
  end

  config.vm.define "web02" do |web02|
    web02.vm.box = "ubuntu/trusty64"
    web02.vm.hostname = "web02"
    web02.vm.network :private_network, ip: "10.11.12.52"
  end
  config.vm.define "lb01" do |lb01|
    lb01.vm.box = "ubuntu/trusty64"
    lb01.vm.hostname = "lb01"
    lb01.vm.network :private_network, ip: "10.11.12.50"
  end
end
