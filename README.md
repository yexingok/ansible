My playground for ansible playbooks.

Configuration should be put into a config folder.

base.yml                   => base 
install-kernel-ml.yml      => install kernel mainalin. (so it contains bbr support)
enable-kernel-bbr.yml      => enable kernel bbr 
install-shadowsocks.yml    => install shadowsocks, need to use config(config/config.json)
install-openvpn.yml        => install openvpn and iptables rules. configs are in config folder which are not commited in the public repo.

