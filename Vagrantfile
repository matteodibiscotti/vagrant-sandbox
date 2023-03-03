Vagrant.configure("2") do |config|

  config.vm.define "myvm" do |m|
    m.vm.box = "hashicorp/bionic64"
    m.vm.network "private_network", ip: "10.1.42.201"
  end
end
