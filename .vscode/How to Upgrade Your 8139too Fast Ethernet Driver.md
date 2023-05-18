## How to Upgrade Your 8139too Fast Ethernet Driver

  
# How to Upgrade Your 8139too Fast Ethernet Driver
 
The 8139too is a Linux kernel driver that supports Realtek RTL-8139 based network cards. It is a fast and reliable driver that can improve your network performance and stability. However, you may need to upgrade your 8139too driver to the latest version if you encounter any issues or want to take advantage of new features.
 
## 8139too download upgrade


[**Download**](https://soawresotni.blogspot.com/?d=2tKFw6)

 
In this article, we will show you how to download and install the latest 8139too driver for your Linux system. We will also provide some tips on how to troubleshoot common problems with the 8139too driver.
 
## Step 1: Download the Latest 8139too Driver
 
The first step is to download the latest 8139too driver from a trusted source. You can find the official 8139too driver on the Linux kernel website[^1^]. The current version of the driver is 0.9.28, which was released on June 29, 2010.
 
To download the driver, you can use the wget command in a terminal window. For example, you can type:
 `wget https://www.kernel.org/pub/linux/kernel/people/jeffgarzik/netdrivers/8139too.c` 
This will download the 8139too.c file to your current directory. You can also specify a different location for the file by adding a -O option to the wget command.
 
## Step 2: Install the Latest 8139too Driver
 
The next step is to install the latest 8139too driver on your Linux system. You will need to have root privileges to do this. You will also need to have the kernel headers and development tools installed on your system.
 
To install the driver, you can use the make command in a terminal window. For example, you can type:
 `sudo make -C /lib/modules/$(uname -r)/build M=$(pwd) modules` 
This will compile and build the 8139too.ko module in your current directory. You can also specify a different location for the module by adding a -o option to the make command.
 
After the module is built, you can install it by typing:
 `sudo make -C /lib/modules/$(uname -r)/build M=$(pwd) modules_install` 
This will copy the 8139too.ko module to the appropriate directory under /lib/modules/$(uname -r)/kernel/drivers/net/. You can also specify a different location for the module by adding a INSTALL\_MOD\_PATH option to the make command.
 
## Step 3: Load and Test the Latest 8139too Driver
 
The final step is to load and test the latest 8139too driver on your Linux system. You will need to have root privileges to do this.
 
To load the driver, you can use the modprobe command in a terminal window. For example, you can type:
 `sudo modprobe 8139too` 
This will load the 8139too.ko module into your kernel and activate your network card. You can also specify some options for the driver by adding them after the modprobe command.
 
To test the driver, you can use some network tools such as ping, ifconfig, ethtool, etc. For example, you can type:
 `ping www.google.com` 
This will send packets to www.google.com and measure the response time. If you get a reply from www.google.com, it means that your network card and driver are working properly.
 
## Troubleshooting Tips
 
If you encounter any problems with the 8139too driver, here are some tips that may help you:
 
- Check if your network card is supported by the 8139too driver. You can use the lspci command in a terminal window to see your network card model and vendor. For example, you can type:
`lspci | grep Ethernet`- If your network card is not supported by the 8139too driver, you may need to use a different driver such as r8169 or rtl8139.
- Check if your kernel version is compatible with the 8139too 0f148eb4a0
