# ThinkPad-like GRUB theme

A clean GRUB theme inspired by the classic ThinkPad palette: black, white, and the iconic red accent.

> Designed for Full HD (1920x1080) displays.

## Preview

This theme is a modified version of [AlexanderKh's Lenovo ThinkPad EFI GRUB theme](https://github.com/AlexanderKh/lenovo-thinkpad-efi-grub-theme), recolored to match a darker ThinkPad aesthetic.

## Installation

### GRUB Customizer

1. Clone this repository.
2. Open **GRUB Customizer**.
3. Go to **Appearance settings**.
4. Use the **+** button to import `theme.tar.gz`.
5. Save the configuration and reboot to verify the result.

### Manual setup

Copy the `theme` directory to your GRUB themes folder and point `GRUB_THEME` to its `theme.txt`:

```ini
GRUB_THEME="/boot/grub/themes/thinkpadlike/theme.txt"
```

Then regenerate your GRUB configuration using the command appropriate for your distribution.

> GRUB configuration is system-critical. Keep a recovery option available and verify the destination path before applying changes.

## Display support

The assets are optimized for a 1920x1080 screen. Other resolutions may require adjustments to fonts, spacing, or background assets.

## Credits

Based on the original work by [AlexanderKh](https://github.com/AlexanderKh/lenovo-thinkpad-efi-grub-theme). Thank you for making the source theme available.
