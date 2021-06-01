# arduino_computer_monitor
Monitor a computer by connecting an Arduino to the motherboard.

More specifically, my program monitors:
* CPU Fan requested speed in % of maximum speed
* CPU Fan axctual speed in RPM
* HDD usage % (+ display a filled square that mimicks HDD LED)
* Temperature (not connected to the motherboard, just uses a temperature sensor)

Overview:
![General overview](/images/overview.jpg?raw=true)

Circuit schematic:
![Circuit schematic](/images/schematic.jpg?raw=true)
I have used an Arduino Leonardo, but I don't use any Leonardo-specific features so an Arduino Uno could be used instead for example.
