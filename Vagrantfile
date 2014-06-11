Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/precise64"
  config.vm.network "forwarded_port", guest: 9200, host: 9200, auto_correct: true
  config.vm.network "forwarded_port", guest: 9300, host: 9300, auto_correct: true
  config.ssh.forward_agent = true
  # config.vm.provider "virtualbox" do |vb|
  #   # Don't boot with headless mode
  #   vb.gui = true
  #
  #   # Use VBoxManage to customize the VM. For example to change memory:
  #   vb.customize ["modifyvm", :id, "--memory", "1024"]
  # end
  #
  # config.vm.provision "puppet" do |puppet|
  #   puppet.manifests_path = "manifests"
  #   puppet.manifest_file  = "site.pp"
  # end
end
