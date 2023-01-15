Vagrant.configure("2") do |config|
  config.vm.box = "archlinux/archlinux"

  config.vm.provision "shell",
    inline: "sudo pacman -Syu --noconfirm; sudo pacman -S --noconfirm sagemath"
end
