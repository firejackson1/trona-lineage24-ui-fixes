# Trona LineageOS 24 UI fixes

This Magisk module targets the 2021 Fire HD 10 and HD 10 Plus (trona) running `24.0-20261112-UNOFFICIAL-trona` from amazon-oss.

- Ends the portrait notification frame just below the notification footer, including **Clear all**.
- Enables notification shade background blur with the rendering settings tested on the Fire HD 10 Plus.
- Enables LineageOS tablet volume-button rotation for the owner account. The module applies the setting once so users can change it afterward.

Download the [module ZIP](./trona-lineage24-ui-fixes.zip).

With Magisk already installed, open **Magisk → Modules → Install from storage**, select this ZIP, and reboot. The installer checks the ROM version and SystemUI checksum before enabling the module.

Remove the module in Magisk and reboot to remove the SystemUI and blur overlays. To undo the persistent volume setting, turn off volume-button reorientation in LineageOS button settings.

Remove the module and reboot before updating the ROM. SystemUI is specific to this build.

The SystemUI and blur changes were verified after reboot using the tablet's rooted ADB overlay. Both volume keys were checked using the tablet's input device at 0° and 180°. Installation through Magisk has not been tested on this tablet.

