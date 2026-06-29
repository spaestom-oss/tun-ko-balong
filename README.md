# tun.ko builder for Huawei E5577 Balong V7R2

Builds `tun.ko` kernel module for Huawei E5577s-321 modem (Balong V7R2, Linux 3.4.5).

## vermagic
`3.4.5 preempt mod_unload ARMv7`

## Usage after download
```bash
# On modem via telnet:
insmod /online/tun.ko
mknod /dev/net/tun c 10 200
chmod 666 /dev/net/tun
```
