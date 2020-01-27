# inspiron

1. Disable secure boot in BIOS
2. Switch from RAID to AHCI in BIOS 
3. Change windows to AHCI
4. Add "nomodeset" when booting from live USB
5. Install
6. Do nomodeset again
7. sudo apt-get update
8. sudo apt-get upgrade
9. sudo apt-get install ubuntu-restricted-extras
10. Reboot
11. Additional drivers, change to NVIDIA
12. Reboot, nomodeset no longer needed
13. sudo apt install pm-utils && sudo pm-hibernate, then power up again - didnt work
14. sudo prime-select intel, or use GUI - saves power and noise - replace "intel" with "nvidia" when needed
15. Reboot
16. sudo apt install gnome-tweaks
17. sudo apt install arc-theme
18. sudo apt install gnome-shell-extensions
19. Change themes
20. sudo vi /usr/share/gnome-shell/theme/ubuntu.css (edit lockDiaglogGroup)
