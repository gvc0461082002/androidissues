# androidissues
listing issues and solutions on my android dev
1.  android-studio----file---sync with gradle
2. kvm permission denied:
This is how I got it to work in Ubuntu 18.04

sudo apt install qemu-kvm
Add your user to kvm group using:

sudo adduser <Replace with username> kvm
If still showing permission denied:

sudo chown <Replace with username> /dev/kvm
