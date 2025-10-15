# Desktop Hub

What this project is
--------------------
This project is a compact desktop USB 2.0 hub built around the GL852G hub controller. It gives you:
- One USB-C upstream port (to connect to a host)
- Two USB-A downstream ports plus one USB-C downstream port
- Per-port power switches (TPS2051C) to protect and limit current to each downstream port
- ESD protection on USB data and power lines

Why I want to build it   I-
----------------------
- Want a small, DIY USB hub for flash drives, keyboards, mice, and low-power peripherals
- Need a hub you can modify (change ESD parts, use different power switches, or tweak traces for higher current)
- Learn about hub controllers, USB signal routing, and SMD assembly

Quick features and limits
-------------------------
- USB 2.0 data speeds supported (Full Speed/High Speed up to USB 2.0 limits)
- Signal traces for D+/D− are routed at 0.2 mm (fine and short — good for USB 2.0)
- VBUS/GND are routed at 0.2 mm in this version due to spacing problems— suitable for flash drives and low-current devices; phone charging will be limited

Licensing
---------
This project is released under the MIT License.