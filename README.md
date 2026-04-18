# 360 Reality Audio Upmix Sony Xperia 5 V Magisk Module

## DISCLAIMER
- Sony apps and blobs are owned by Sony™.
- The MIT license specified here is for the Magisk Module only, not for Sony apps and blobs.

## Descriptions
- Equalizer sound effect ported from Sony Xperia 5 V (pdx237) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Global type sound effect
- Wireless Headphones is forced certified (so it doesn't mean your wireless headphone is originally certified)

## Sources
- https://dumps.tadiphone.dev/dumps/sony/pdx237 sssi-user-14-67.1.A.2.229-1-release-keys
- libmagiskpolicy.so: Kitsune Mask R6687BB53

## Screenshots
- https://t.me/ryukimodsscreenshots/26

## Changelog

v0.7
- Does not disable raw playback (You can use Audio Compatibility Patch Reborn Magisk Module instead)

v0.6
- Fix wrong target in latest KernelSU

v0.5
- Tidy up aml.sh
- Exclude audioeffectshaptic.xml
- Abort installation if fail to mount mirror system
- Fix wrong file permissions in some ROMs

v0.4
- Improve /odm and /my_product support detection

v0.3
- Add Action button to clear apps caches
- Fix architecture detection in some weird ROMs
- Fix bug in uninstall.sh

v0.2
- Fix conflict with in-built camera
- Fix INTERACT_ACROSS_PROFILES permission

v0.1
- Initial release

## Requirements
- arm64-v8a or armeabi-v7a architecture
- Android 11 (SDK 30) and up
- HIDL audio service
- Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- If you are using KernelSU, you need to disable Unmount Modules by Default in KernelSU app settings and install https://github.com/KernelSU-Modules-Repo/meta-overlayfs first
- Install this module https://devuploads.com/d194tbnulu0b via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Install AML Magisk Module https://t.me/ryukinotes/34 only if using any other else audio mod module
- Reboot
- If you are using KernelSU, you need to allow superuser list manually all package name listed in package.txt (and your home launcher app also) (enable show system apps) and reboot afterwards
- If you are using SUList, you need to allow list manually your home launcher app (enable show system apps) and reboot afterwards

## Known Issues
- Sample music can't be played (requires ROM codec support)
- You need to clear selection first if you change between headphones personalization to take effect
- Camera capture to right and left ear can't be detected. Just Retake and choose MANUAL SHOOTING.
- Camera issue if using KernelSU

## Optionals
- https://t.me/ryukinotes/44
- Global: https://t.me/ryukinotes/35
- Stream: https://t.me/ryukinotes/52

## Troubleshootings
- Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- @HuskyDG
- @ahnet_h
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
- https://t.me/ryukinotes/25


