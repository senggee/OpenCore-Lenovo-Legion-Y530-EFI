# OpenCore-0.8.2-Lenovo-Legion-Y530-EFI

This is my EXPERIMENTAL EFI file, use it at your own risk.


MUST DO:

Enter Advance BIOS setting ( "Fn" + "D" + "O" keys) press simultaneously

FOLLOWED BY changing the BIOS setting:

Sercurity --> Secure Boot [Disable]

Advanced --> Debug Settings --> Kernel Debug Serial Port [Legacy UART]

Force unlock on all GPIO pads : Enabled without this Trackpad will not work on macOS 

Advanced -> PCH-IO Configuration -> Security Configuration -> Force unlock on all GPIO pads [Enable]

![Screenshot (48)](https://user-images.githubusercontent.com/73149628/118384085-fb442080-b635-11eb-8b9c-d3386fdd45c2.png)
![Screenshot (50)](https://user-images.githubusercontent.com/73149628/118384086-fd0de400-b635-11eb-8156-c023620dc575.png)

Working:
Display brightness
Audio
Ethernet
WIFI and TrackPad Buttons

Not Working:
HDMI
