[![Snap Status](https://build.snapcraft.io/badge/ogra1/uboot-tools-snap.svg)](https://build.snapcraft.io/user/ogra1/uboot-tools-snap)

# uboot-tools snap

This snap contains a separate set of the u-boot tools from a
"make tools-only" build run. Note that due to snapcraft restrictions
tools that come with an underscore in the name need to be used with a dash
in its place (i.e. uboot-tools.fit_info becomes uboot-tools.fit-info).

## Shipped applications

uboot-tools.dumpimage

uboot-tools.fdtgrep

uboot-tools.img2srec

uboot-tools.jtagconsole

uboot-tools.mkenvimage

uboot-tools.mkimage

uboot-tools.ncb

uboot-tools.netconsole

uboot-tools.proftool

uboot-tools.fit-check-sign

uboot-tools.fit-info

uboot-tools.gen-eth-addr

uboot-tools.gen-ethaddr-crc

## Using the snap on Ubuntu Core

If you use this snap on an Ubuntu Core installation, please make sure to connect the home interface using

```snap connect uboot-tools:home```

Else you will need to use ~/snap/uboot-tools/current/ as your workdir when using them.
