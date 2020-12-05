sudo apt update
sudo apt install cpu-checker

kvm-ok
```
INFO: /dev/kvm exists
KVM acceleration can be used
```

sudo apt-get install qemu-kvm libvirt-daemon-system libvirt-clients bridge-utils

systemctl is-active libvirtd
