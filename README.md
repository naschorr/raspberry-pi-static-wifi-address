# raspberry-pi-static-wifi-address

Known working settings for having a wireless pi with a static address

---
interfaces goes in /etc/network/, and wpa_supplicant.conf goes in /etc/wpa_supplicant/.

You'll also need to add in the settings for the network you're trying to connect to. It's also a good idea to back up your current settings before pasting these in.

Obviously this isn't a magic bullet, but it works for my Model B even after the Raspberry Pi 2 update that broke some other things.
