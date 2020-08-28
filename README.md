# proxmox-pfsense

PFsense running as a Proxmox VM

## Installation

VM setup in Proxmox:

run the following

``` shell
bash <(curl -s https://raw.githubusercontent.com/shepner/proxmox-pfsense/master/proxmox/create-vm.sh)
```

[Disable Hardware Checksum Offloading](https://docs.netgate.com/pfsense/en/latest/virtualization/virtio-driver-support.html)

