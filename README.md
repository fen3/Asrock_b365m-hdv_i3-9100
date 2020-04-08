# Asrock_b365m-hdv_i3-9100

MacOS 10.15.2 Catalina 

Hardware:

ASRock B365M-HDV

Intel i3-9100

HP S700 128G SSD

2x CUSO 16GB 2666

I have not tested NVME or the M.2 slot and my custom USB Port Limit patch (USBPorts.kext) probably disables it's internal USB Port.

I have disabled some of the front bracket USB Ports and set the black ports on the back of the motherboard to be USB2 only to be under the 15 port limit. Use USBInjectAll.kext and remove CLOVER/kexts/Other/USBPorts.kext if you want to temporarily enalbe all USB Ports so that you can customize USB settings. [1][2][3]

[1] https://hackintosher.com/forums/thread/list-of-hackintosh-usb-port-limit-patches-10-15-updated.467/

[2] https://github.com/RehabMan/OS-X-USB-Inject-All

[3] https://github.com/headkaze/Hackintool


