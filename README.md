# grub-theme-slim
Theme for GRUB2

## How to use
1. Copy ```slim``` directory to ```/boot/grub/themes/```
2. Change theme in ```/etc/default/grub```
```
GRUB_THEME="/boot/grub/themes/slim/theme.txt"
```
3. Regenerate grub config
```
grub-mkconfig -o /boot/grub/grub.conf
```


## How to change default GRUB2 font
1. Copy ```fonts/terminus-bold-18.pf2``` to ```/boot/grub/fonts/```
2. Change font in ```/etc/default/grub```
```
GRUB_FONT="/boot/grub/fonts/terminus-bold-18.pf2"
```
3. Regenerate grub config
```
grub-mkconfig -o /boot/grub/grub.conf
```


## How to use Ventoy theme
Copy ```ventoy``` directory to flash card root ```/```

---
#### That's it! Enjoy slim GRUB2 theme!
