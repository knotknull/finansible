# NOTE:  the acs = Ansible Control Server, web = Web server, db=Database
#
# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

  config.vm.define "acs" do |acs|
    acs.vm.box = "centos/7"
    acs.vm.hostname  = "acs"
    acs.vm.network "private_network", ip: "192.168.33.10"
    acs.vm.synced_folder "share/", "/vagrant/share"
  end

end
