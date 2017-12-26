# RTL8192EU

Linux driver for RTL8192EU. The master branch is based on Realtek Version

**00009385-RTL8192EU_linux_v5.2.19_24763_COEX20170113-0046.20171031**

It has been modified to build cleanly for kernels through v3.10.49

Run the following commands in the Linux terminal.

```shell
git clone https://github.com/wsyco/RTL8192EU_Linux.git
cd RTL8192EU_Linux
make
make install
modprobe -v 8192eu
lsmod | grep 8192eu
```

