1. git clone https://github.com/qdk0901/openwrt-uboot-mt7628.git

2. copy openwrt-uboot-mt7628 folder to openwrt_source/package/boot/

3. select uboot-mt7628 package under menuconfig in bootloader category

4. building uboot with under commands
```
   make package/uboot-mt7628/prepare V=s
   make package/uboot-mt7628/compile V=s
```
5. uboot.bin will generated under openwrt_source/bin folder
