# OpenWRT build with full support for Sierra Wireless EM9191

Compiled using official firmware from Sierra Wireless for EM9191 in USB MBIM mode for the Raspberry PI 4 Model B.

Provided scripts for hotplug via USB and initial configuration for EM9191 as WAN device.

Drive Link for tarball:
https://drive.google.com/file/d/1T5Ss5T06zlsR6LzxRM7sgjT3XP7bfztf/view?usp=sharing

Modified Structure:
- files/etc/hotplug.d
- files/etc/init.d
- files/etc/mbim-network.conf
- package/base-files/files/etc/uci-defaults/99_net-gen-eth0-wwan
- package/base-files/files/etc/uci-defaults/99_net-gen-eth1-wwan
- package/base-files/files/etc/uci-defaults/99_net-gen-wan-wwan
- package/base-files/files/etc/uci-defaults/99_net-gen-dhcp-wwan
- package/kernel/qcserial
- package/kernel/usb_wwan
