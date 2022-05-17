#headlesspi-new-defaults



### HowTo::
1. Clone this repository: `git clone {this_repo_url}`
2. Plug the sd-card into the computer with the restore image copied. 
3. Copy source files to boot partition. `cd headlesspi-new-defaults/src && cp -Rv ./* /media/$USER/boot/`
4. Change `wpa_supplicant.conf` to match your wifi settings.`nano /media/$USER/boot/wpa_supplicant.conf`

Enjoy your headless pi. 

