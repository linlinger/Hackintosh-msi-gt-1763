MSI GT-1763
device-specs：
i7 4700MQ with Intel HD Graphics 4600
AMD Radeon RX 480

Working
Graphics（Including hardware acceleration）
Sound
CPU freq changes
Ethernet
Not working：
Sleep/wake
wireless-based features（airdrop handoff etc.）

HOW TO CHOOSE CONFIG FILE
If your graphics card is compatible with MacOS Mojave. Use config.plist directly.

If you have a AMD rx 480 or other AMD RX graphics card.use config-enable-hardware-acceleration.plist boot first.Once you make sure hardware acceleration is turned on.
Boot with config.plist instead.There's no need 4u to use that.

If you have Mojave unsupported DGPU。use config-no-Mojave-compatible-DGPU。plist