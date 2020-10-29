# Various Tips and Tricks for Linux

Note: In progress

## POP!_OS - Dual Boot with GRUB on UEFI

Once Grub is installed, run:

'''
sudo grub-install
sudo cp /boot/grub/x86_64-efi/grub.efi /boot/efi/EFI/pop/grubx64.efi
grub-customizer
'''
