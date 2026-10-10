# Awesome Steam Frame

A curated list of steam frame compatible software, hardware and more.

## Table of contents

- [Emulation Layers](#emulation)
- [Tools](#tools)
    - [Video Playing / Streaming / Recording](#video-playing--streaming--recording)
    - [Eye Tracking](#eye-tracking)
    - [Controls](#controls)
- [Guides & Scripts](#guides-and-scripts)
- [3rd Party Accessories](#3rd-party-accessories)
    - [Prescription Lenses](#prescription-lenses)
- [Games](#games)

--------------------

## Emulation Layers

- [FEX](https://github.com/FEX-Emu/FEX) - A fast usermode x86 and x86-64 emulator for Arm64 Linux.
- [Lepton](https://gitlab.steamos.cloud/frame-public/lepton/) - A tool for use with the Steam client which allows games which are exclusive to Android to run on the Linux operating system.

--------------------

## Tools
- [Frame Developer Tools](https://gitlab.steamos.cloud/frame-public/frame-developer-tools) - Various developer-related tools and test programs.
- [Steam Frame Hub](https://verified.steamframehub.com/) - An independent publication and community dedicated to Valve’s Steam Frame.
- [VRDEVNET](https://vrdev.net/) - An independent publication and community dedicated to VR related projects.
- [Frame Perf Overlay](https://github.com/sasaken1102r/frame-perf-overlay) - Performance overlay for Steam Frame: fps, CPU/GPU, temperatures, power, battery and Steam Link link in SteamVR (unofficial) / Steam Frame.
- [FrameMate](https://github.com/nailuj05/framemate) - A companion app for the Steam Frame: mirror the headset to your phone, keep an eye on battery, controllers, downloads and what's playing.
- [petplay](https://github.com/goodpuppies/petplay) - PErsonal Terminal Project overLAY.
- [Chromium WebXR](https://github.com/saphid/chromium-webxr-steam-frame) - Chromium with immersive WebXR on the Steam Frame: build script, SteamVR fix, and a Steam library installer.
- [frame-autopass](https://github.com/bod09/frame-autopass) - Automatic colour/IR passthrough switching for the Steam Frame with the Arcturus Vision colour module.
- [ovrplugin-openxr-shim](https://github.com/daniel-lynch/ovrplugin-openxr-shim) - An independent OpenXR reimplementation of Meta's OVRPlugin ABI, so VrApi-era Quest VR titles can run on non-Meta OpenXR runtimes (Monado, Steam Frame). Interoperability — original code only.
- [VR Mod Vibecoding Wizard](https://github.com/bigbossafman/VR-Mod-Vibecoding-Wizard) - Turn a flat PC game into a full VR mod: 6DoF, motion controls, physics hands, holsters, reloads, IK body, in-VR settings menu. A Claude skill that interviews you, plans the build, and tracks bugs.
- [LiquidAss-Frame](https://github.com/MichaelScottsman/LiquidAss-Frame) - Liquid glass theme and virtual music player for Steam Frame.
- [PhoneCast VR](https://github.com/bangfireball/Phonecast_VR) - Mirror your phone into VR, check notifications, watch videos with optional phone audio, and interact using your controllers—all while a standalone game runs underneath.

### Video Playing / Streaming / Recording
- [Frame Mic Tuner](https://github.com/sasaken1102r/frame-mic-tuner) - SteamVR dashboard panel to switch the Steam Frame mic's echo cancellation and noise suppression (unofficial).
- [Stream Frame](https://streamframe.app/) - The missing streaming and recording utility for Steam Frame.
- [MatineeVR](https://embedding-shapes.itch.io/matineevr) - An experimental, open-source VR video player built specifically to run standalone on Steam Frame.
- [framecorder](https://framecorder.coah80.com/) - A recorder for the steam frame that runs on the headset itself. record, clip, sync.
- [video2webxr](https://github.com/phit/video2webxr) - Watch YouTube 360°/VR180 videos and videos on other sites in your PC VR headset via WebXR (Chromium extension).

### Eye Tracking
- [frameeyeosc](https://github.com/konsti219/frameeyeosc) - Transmitting Steam Frame Eye Trackign Data via OSC.
- [vrcft-steam-frame](https://github.com/hakumaguro/vrcft-steam-frame) - Eye tracking for the Steam Frame in VRChat, through VRCFaceTracking (VRCFT): per-eye gaze, real blinks and winks.
- [FrameEye Helper](https://github.com/miyu0-bit/frameeye-helper) - Installs frameeyeosc on your Steam Frame for you, so you get eye tracking in VRChat without the terminal stuff.

### Controls
- [FrameTop](https://github.com/DeeJanuz/frametop) - Multi-screen KDE Plasma desktop and universal 3D mouse for the Valve Steam Frame (SteamVR).
- [FrameTop (AZumD)](https://github.com/AZumD/frametop) - Fork of Frametop with with spatial profiles, additional anchoring and follow modes, Steam Frame eye-gaze-driven screen attention, desktop recovery, pointer-scaling fixes, and other experiments around using the Steam Frame as a spatial desktop.
- [Frame Passthrough Shortcuts](https://github.com/KominoVR/frame-passthrough-shortcuts) - Change Steam Frame passthrough modes from your controllers.
- [Frame Color](https://github.com/beko-kerbecotton/framecolor) - FrameColor lets you adjust the Steam Frame's display colors from the SteamVR dashboard inside the headset.
- [Space Calibrator](https://store.steampowered.com/app/3368750/Space_Calibrator/) - Use tracked VR devices from one company with any other. [Source](https://github.com/hyblocker/OpenVR-SpaceCalibrator)
- [Frame Control](https://github.com/saphid/frame-control) - Frame Control: a free, open-source app for Valve Steam Frame on macOS, Windows, Linux and iPhone. View the headset, install games and apps, transfer files, and manage your Frame.
- [FrameYap](https://github.com/baketnk/frame-yap) - On-device voice typing for Steam Frame: hold a button, speak, review, type. Local speech recognition, no cloud.
- [frame-unboundedMouse-vibed](https://github.com/Andalu30/frame-unboundedMouse-vibed) - An experimental steamvr driver to control the laser pointer of Steam Frame with a mouse.
- [fuelCell](https://github.com/juanramosjr1/frame-voice) - Speak into any text box on your Steam Frame: the Steam store search, a browser, Discord. It also gives you easy Copy, Paste and Select all using your controllers.
- [Steam Frame Dictation](https://github.com/khvn26/steam-frame-dictation) - Offline dictation on the Steam Frame.
- [frame-voice](https://github.com/techieyann/frame-voice) - Voice dictation for Steam Frame. Speak into a text field using your controllers, without a keyboard or an always-on microphone.

--------------------

## Guides & Scripts

- [Post About Initial Problems](https://www.reddit.com/r/SteamFrame/comments/1wsgihj/how_i_solved_all_my_problems_with_my_frame/) - A liked post on reddit describing on most common problems after the initial release.
- [Valve TroubleShooting Script](https://github.com/ValveSoftware/SteamVR-for-Linux/blob/master/frame-dongle-troubleshoot.sh) - A very quickly-written script to try to track down and spot the most-commonly-seen problems with using the Steam Frame wireless dongle on Linux.
- [Arch Linux Streaming Setup Guide](https://www.reddit.com/r/SteamFrame/s/WJzYvCwetQ) - A detailed guide on how to stream from an Arch Linux remote machine.

------------------

## 3rd Party Accessories

- [Arcturus Vision Camera](https://arcturus.vision/) - 5K HDR color passthrough and more for Steam Frame.
- [Spigen Controller Grips](https://www.amazon.com/dp/B0GV1LQT9N) - Padded Comfort Strap, Adjustable Size, Non-Slip Dotted Grip, Silicone Fit for Steam Frame. (NOTE: These are known to cover some of the tracking IR thus degrading the tracking, especially the finger tracking.)
- [Fossmon VR Headset Stand](https://www.amazon.com/dp/B0HFQLHDDY) - Universal headset stand compatible with Meta Quest 3 3S 2, Vision Pro, Valve Index and Steam Frame.
- [PD100 Mount](https://github.com/DeeJanuz/steam-frame-pd100-mount) - 3D-printable mounts that carry a BoboVR PD100 battery above or below the Valve Steam Frame's rear battery pod.
- [Steam Frame Controllers Gamepad Coupler](https://makerworld.com/en/models/3404888-steam-frame-controllers-gamepad-coupler#profileId-3877306) - 3D printable Steam Frame controller adapter that merges two controller into one.
- [Frame Workshop](https://github.com/Nieko27/Frame-Workshop) - A repo for all things steam frame hardware.
- [Babble Mouth Tracker Pro](https://babble.diy/store/babble-tracker-pro/) - Face/mouth tracker by Project Babble.
- [DIY Top Strap](https://www.printables.com/model/1861609-steam-frame-diy-top-strap-2-clips-webbing) - 3D printable top strap for the Steam Frame.

### Prescription Lenses

- [Zenni Prescription Lenses](https://www.zennioptical.com/p/steamframe-vr-prescription-insert/VR80004) - Official Partnership with Valve.
- [VR Optician Prescription Lenses](https://vroptician.com/prescription-lens-inserts/valve-steam-frame)
- [WIDMOvr Prescription Lenses](https://widmovr.com/product/steam-frame-prescription-lens-adapters/)
- [AMVR Prescription Lenses](https://www.amvrshop.com/products/amvr-nl2-prescription-lenses-steam-frame)
- [VR-Rock Prescription Lenses](https://www.vr-rock.com/products/steam-frame-prescription-lenses)

### Cases

- [Harbor Freight Apache 3800 (US)](https://www.harborfreight.com/3800-weatherproof-protective-case-large-black-63927.html) - This is not a case officially designed for Steam Frame but there is [a reddit post](https://www.reddit.com/r/SteamFrame/s/HkRnAJCRWS) saying it fits perfectly.
- [Txtcu Quest 3 Case (EU)](https://www.amazon.de/-/en/Txtcu-Quest-Bag-Accessories-Controllers/dp/B0D9S2K8H6?th=1) - Mini Case with hard shell for Quest 3/3S but Steam Frame fits as well.
- [HMF ODK100 Outdoor Case (EU)](https://www.amazon.com.be/dp/B08K3K5NHY?ref=cm_sw_r_cso_cp_apan_dp_1MJJBP01JV5TPD8SJK0M&ref_=cm_sw_r_cso_cp_apan_dp_1MJJBP01JV5TPD8SJK0M&social_share=cm_sw_r_cso_cp_apan_dp_1MJJBP01JV5TPD8SJK0M&th=1&language=en_GB) - Strong outdoor case with pre-cut foam for cameras. [hagglezon link](https://www.hagglezon.com/en/l/B08K3K5NHY/hmf?utm_campaign=web_share&utm_content=B08K3K5NHY)
- [JYS-SDM016 Quest 3 Case (AliExpress)](https://pl.aliexpress.com/item/1005013181166491.html?spm=a2g0o.productlist.main.5.2d41618clQpIaA&algo_pvid=b9002be5-aee5-4346-bb50-8c23ff1477f3&algo_exp_id=b9002be5-aee5-4346-bb50-8c23ff1477f3-4&pdp_ext_f=%7B%22order%22%3A%223%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21EUR%2145.32%2140.79%21%21%21332.75%21299.49%21%400b884c0217912874664135146e1492%2112000060480428620%21sea%21FR%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Ac5dd7e13%3Bm03_new_user%3A-29895&curPageLogUid=Shro3ee1SgJX&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005013181166491%7C_p_origin_prod%3A&gatewayAdapt=usa2pol4itemAdapt) - Hard Shell Case for Steam Frame/Meta Quest 3.
------------------

## Games

- [FramePort](https://github.com/spoopyghosty0/frameport) - Port games to work with the Steam Frame.
- [Quest2Frame](https://github.com/vesper8/Quest2Frame) - Transfer Quest games to Steam Frame (Original repository was taken down. This is a fork).
- [Wiicompiled VR Frame](https://github.com/mitch030504/Wiicompiled_VR_Frame) - Wiicompiled OpenXR for steam frame.
