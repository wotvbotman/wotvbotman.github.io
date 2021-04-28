---
layout: post
title:  "60 FPS WOTV on BlueStacks"
date:   2021-04-27 16:00:00 -0500
categories: emulator bluestacks
---

After playing 60 FPS WOTV on BlueStacks I don't want to go back to my mobile device.  I prefer playing on my emulator because of those buttery smooth animations.  

## How To

I've included steps that have worked for me in hopes that they will work for you as well.

### 01. Download BlueStacks 4

If you don't have it already, head over to the [BlueStacks site](https://www.bluestacks.com/) and download version 4

### 02. Open BlueStacks multi-instance manager

Once installed, open the BlueStacks multi-instance manager and click the `New Instance` button 

![Open the BlueStacks multi instance manager](/assets/img/bs_high_fps_howto/01_multi_instance_lrg.jpg)

### 03. Create a fresh instance

Choose the first option that says `Fresh Instance` to create your new instance

![Create a new instance](/assets/img/bs_high_fps_howto/02_fresh_instance_lrg.jpg)

### 04. Choose Android Version: Nougat 32-bit with large virtual addresses

When prompted to choose an Android version, open the dropdown menu and select `Nougat 32-bit (Large virtual address)`

![Select Android version "Nougat 32-bit with large virtual addresses"](/assets/img/bs_high_fps_howto/03_android_version_lrg.jpg)

### 05. Start the new BlueStacks instance

Start the BlueStacks instance you just created, and once it's running open the options menu.  The option menu will be the button in the upper right, between the `?` and `-` buttons.

![Open the new instance's settings](/assets/img/bs_high_fps_howto/04_settings_tab_lrg.jpg)

### 06. Engine settings

Click on the Engine tab and set the following options:

* **Graphics engine:** `Compatibility`
* **Graphics renderer:** `OpenGL`
* **GPU settings:** enable `Prefer dedicated computer graphics` (if you have an NVIDIA GPU)
* **ASTC texture:** `Disabled`
* **Performance:** **CPU** `High (4 Cores)` and **RAM** `High (4 GB)`

### 07. Frame rate settings

At the bottom of the Engine tab you'll find a frame rate slider.

1. Set the frame rate to `1`
2. Click the check box to `Enable high frame rates`
3. Then slide frame rate up to `30`

### 08. Set preferences

Click on the preferences tab and disable most of them, consult the settings listed below, most are optional but can affect performance.

#### Performance settings

- [ ] Standard Android switching between apps
- [ ] Close web pages when running game
- [x] Enable periodic memory trimming

#### Game control settings

- [ ] Enable gamepad detection
- [x] `optional` Show warning before deleting a control scheme 

#### Platform settings

- [x] `optional` Add desktop icons for installed apps 
- [ ] Show gaming summary on close
- [ ] Show warning before deleting a macro script
- [ ] Allow BlueStacks to connect with Discord
- [ ] Enable Android Debug Brudge (ABD)

#### Input debugging

- [ ] Show visual feedback for taps
- [ ] Show pointer location with current touch data

### 09. Set device profile

Click on the Advanced tab and set the device profile to `Google Pixel 2XL`

![Device profile set to Google Pixel 2XL](/assets/img/bs_high_fps_howto/09_device_profile.jpg)

### 10. Final steps

A note about a quick with WOTV's frame rate.  It seems to run at half the device's settings if it is set over 30, but this only occurs at launch.  So after launching the game you can open the emulator's settings and raise the frame rate from 30 to 60.  You'll have to do this each time if you want those buttery smooth frames but it's worth it.

As a side effect, this configuration of BlueStacks has been running very stable for me.

## Credits

Thanks to `u/Niatpac` on Reddit for this information.  Steps come from their [original post](https://www.reddit.com/r/wotv_ffbe/comments/mgnve4/bluestacks_4_60_120_fps_guide/).  I rewrote the steps in my own words and took new screenshots to present them here.