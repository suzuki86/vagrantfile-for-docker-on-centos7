Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "ansible/main.yml"
    ansible.install = true
    ansible.verbose = "vvv"
  end
end
