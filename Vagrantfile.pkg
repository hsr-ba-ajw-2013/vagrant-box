Vagrant::Config.run do |config|
  config.vm.box = "squeeze64"
  config.vm.box_url = "http://dl.dropbox.com/u/937870/VMs/squeeze64.box"

  config.vm.forward_port	80, 9000	# HTTP
  config.vm.forward_port	5432, 9001	# PostgreSQL
end
