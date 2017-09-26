# rpi-cluster
## prepare RPI
- Install ubuntu http://cdimage.ubuntu.com/ubuntu/releases/16.04/release/ubuntu-16.04.3-preinstalled-server-armhf+raspi2.img.xz
- Copy ssh key to nodes - https://github.com/garthvh/ansible-raspi-playbooks
- TODO update ansible with https://gist.github.com/gwillem/4ba393dceb55e5ae276a87300f6b8e6f

## ansible for cluster setup
- setup k8s
- setup minio - distributed
- setup pachyderm

## example cluster
### components
- 4 x Raspberry Pi 2 B
- 1 x DC supply 5V 4A (mini usb out)
- 1 x 5 ports switch
- 4 x ethernet cables
- 4 x micro sd 16gb cards
