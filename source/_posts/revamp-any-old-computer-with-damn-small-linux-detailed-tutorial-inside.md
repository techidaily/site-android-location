---
title: Revamp Any Old Computer with Damn Small Linux - Detailed Tutorial Inside
date: 2024-08-15T19:32:40.423Z
updated: 2024-08-16T19:32:40.423Z
tags:
  - desktop
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/X2FPx6DXvcnTE32wDJ3Lj6-320-80.jpg
---

## How to Rebirth Your Vintage PCs Using Damn Small Linux – The Easy Way

Damn Small Linux is a lightweight Linux distro aimed at older and lower spec PCs just like the Asus Eee PC that we have from 2007\. The last release was way back in 2012, and since then the project has been on hiatus. Originally weighing in at 50MB back in 2012, Damn Small Linux 2024 Alpha release is a bulkier 700MB, and this hard limit means that it can be written to a blank CDR.

 Based on Debian and antiX,[Damn Small Linux 2024](https://www.damnsmalllinux.org/) uses Fluxbox and JWM window managers. These are lightweight alternatives to Gnome, KDE etc and are often used for distros targeting lower spec machines. There is a limited range of pre-installed software, covering web browsers, text editors, code editors, media playback and email. Because it is a Debian-based system, we can install applications using the apt package manager.

 The Asus Eee PC 4G was the first netbook from Asus and it contained an Intel Celeron 900 MHz CPU, but this was underclocked to 700 MHz to save power. Originally shipping with 512MB of RAM, our unit has been upgraded to 1GB. An internal 4GB eMMC is our only means of storage.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/JNKozDryqKdwftuyVWAqV5-320-80.png)

 (Image credit: Tom's Hardware)

 Damn Small Linux 2024 runs well on the venerable Asus Eee PC. Basic web browsing, text editing and general computing tasks are achievable. More advanced tasks, high definition video and image editing will depend on the age of your machine. On the Eee PC we found YouTube playback was not possible, because the CPU wasn’t strong enough to load all of the page elements. A newer machine is required for that. Something from the early 2010s, perhaps a Core2Duo or better and you have a workable spare machine.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

## For this project you will need

* A USB stick (1GB or greater)
* An old PC with 4GB or greater HDD / SSD
* 1GB or more RAM
* Internet connection (Ethernet or Wi-Fi)

## Creating a Damn Small Linux 2024 boot USB

 The first step in the process is to create a bootable USB stick and for this we will need the Damn Small Linux 2024 ISO image and a copy of Rufus. Rufus will write the ISO image to the USB stick so that we can boot from it.

 1.**Download the latest ISO version of** [**Damn Small Linux 2024**](https://www.damnsmalllinux.org/2024-download.html) **to your computer.**

 2.**Download and install** [**Rufus.**](https://rufus.ie/en/)

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 3.**Insert a USB stick (1GB or larger) and open Rufus.**

 4.**Select your USB stick as the Device** , then for Boot Selection**select Disk or ISO image and click SELECT.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/baQXPzYCDw9eq9wf9YrQXA-320-80.jpg)

 (Image credit: Tom's Hardware)

 5.**Select the Damn Small Linux 2024 ISO image and click Open.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/j3mBhzFS7tmDqEckBrWdQA-320-80.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 6.**Click START** to write the ISO to the USB stick. The ISO image is only 700MB and won’t take long to write to the USB stick. When done,**click CLOSE to exit Rufus.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/yu9EYu9BTTuGGjBtXNuEJA-320-80.jpg)

 (Image credit: Tom's Hardware)

 7. **Remove the USB stick from the computer and insert it into the recycled machine.**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## Installing Damn Small Linux 2024

 Now that we have a bootable USB stick, our focus moves to the old PC that we wish to reuse. We will first boot from the USB stick and ensure that it reaches the Damn Small Linux 2024 desktop.

 1\. With the USB stick inserted, **power up the computer and press the correct key to enter the boot selection.** The key can be ESC, F2, DEL or F12\.

 2.**Select Damn Small Linux 2024, hacked from antiX 23** and**press Enter.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/VX3He6Ti2rXuBRUXryans9-320-80.png)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 3.**Wait for Damn Small Linux to boot** and**click on the Installer icon** to start the installation process.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/8ruHFaJdsNupjFtvbQehm9-320-80.png)

 (Image credit: Tom's Hardware)

 4.**Wait for the installer to check your installation media** (the USB) for errors.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/PvyNXHHvZqzg9U2xzwU9CA-320-80.png)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 5.**Set your keyboard layout and click Next when ready.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/pyrBdYG3Uqu4UxbURuo5U9-320-80.png)
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 6. **Install Damn Small Linux to use the entire hard drive and click Next to progress.** Advanced users may want to dual boot with another Linux distro or Windows, or to only use a partial amount of the drive. This is left as an exercise for advanced users.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/yqysCHTCs2mmqroE2YtZL9-320-80.png)

 (Image credit: Tom's Hardware)

 7.**Click OK to format the drive.** This will prepare the drive for the Damn Small Linux installation process.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/8HggdEvF2DKDFVbUVmCqB9-320-80.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 8\. While the installer copies the files,**setup your locale and timezone then click Next.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/2zBeZ2Ezr6diBMHTuYQZ39-320-80.png)

 (Image credit: Tom's Hardware)

 9. **Next setup your unprivileged user, and optionally a root user account. Click Next to move on.** Your unprivileged user is automatically added to the sudo group and so can temporarily elevate their privileges. But often, having a root admin user is an extra level of[security](https://www.tomshardware.com/tag/security) should you accidentally break the main user account.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/bwm3cbDBvEeMPW7bFSGe3A-320-80.png)

 (Image credit: Tom's Hardware)

 10. **Ensure that automatically reboot checkbox is checked, and click Finish to reboot.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/vVszmiobWW4GyN9D2xCLu8-320-80.png)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Using Damn Small Linux 2024 for the first time

 Damn Small Linux 2024 doesn’t feel too different from more mainstream Linux distros. It may look different when compared to the “high gloss” distros for more modern machines, but under the hood is Debian, and this makes us feel right at home.

 1. **If prompted on boot, select the Damn Small Linux 2024 option from GRUB.** GRUB is a boot menu where we can choose which operating system to boot from.

 2. **At the login prompt, enter your username and press Enter to move to the password box. Enter the password and press Enter to login.** Typically we would use TAB to navigate between the lines, but this did not work with Damn Small Linux.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/ZFdWZ4QpfABaJ9bbULSrk8-320-80.png)

 (Image credit: Tom's Hardware)

 3.**Left click on Menu to open the main menu.** You can also right click to bring up the menu at your current mouse position.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/G8vXVZ6gyiBBpriaEhooY8-320-80.gif)

 (Image credit: Tom's Hardware)

Quick links to apps are found at the top of the list.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/HqrNrNtz2VMYg9qbGtx8A8-320-80.png)

 (Image credit: Tom's Hardware)

 The Applications menu contains all of the applications that come pre-installed. We can add more apps via the terminal. Underneath the desktop is a Debian install which we can update using the apt package manager. You will need an Internet connection before attempting to do this.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/PceAwi5SHK8ZN4cZQRRVS7-320-80.png)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 1.**Right click and select Terminal from the menu.**

 2.**Update the repositories.** This checks our list of installable software against a list on a remote server.

```
sudo apt update
```

 3.**Search for an application.** We wanted to install the Geany text editor, so we searched the repositories for geany. **Scroll through the returned information to discover the application.**

```
sudo apt search geany
```

 4. **Install the app using apt. Press Enter to run the command, and wait for the installation to complete.**

```
sudo apt install geany
```

 5.**Run the app from the terminal using its name and press Enter.**

```
geany
```

 The alternative to the terminal is the Manage Packages application, found in the Control Center >> Software. This is a simpler, guided means to keep your system up to date.

 The Control Center is where we can make changes to the system. For example we can make Wi-Fi and Network connections, update system time and manage packages.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/fpp3uEkLvKHzjMDdGUpkr7-320-80.gif)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 (Image credit: Tom's Hardware)

 Damn Small Linux 2024 is a fun way to resurrect an older machine. We wouldn’t spend our entire work day using such an old machine, but it can be useful to have a spare machine for the kids to hack on. It can also be useful when we need focus, a low-spec machine will struggle to run multiple applications, forcing us to complete a task.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-honor-magic-5-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-vivo-y100-5g-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-sony-xperia-1-v-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-understanding-the-fundamentals-of-online-tales/"><u>2024 Approved  Understanding the Fundamentals of Online Tales</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-samsung-galaxy-a34-5g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Samsung Galaxy A34 5G | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-lava-yuva-3-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-motorola-moto-g73-5g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/does-apple-iphone-7-have-find-my-friends-drfone-by-drfone-virtual-ios/"><u>Does Apple iPhone 7 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/easy-to-follow-tips-for-hassle-free-high-dynamic-range-imaging/"><u>Easy-to-Follow Tips for Hassle-Free High Dynamic Range Imaging</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-hardware-insights-from-toms-technology-hub/"><u>Expert Hardware Insights From Tom's Technology Hub</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/ezvid-for-mac-the-ultimate-slideshow-and-video-making-solution-for-2024/"><u>Ezvid for Mac The Ultimate Slideshow and Video Making Solution for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-motorola-edge-40-neo-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Motorola Edge 40 Neo Devices | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-vivo-y77t-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Vivo Y77t Devices | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-realme-12-proplus-5g-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-persistent-cursor-blink-a-detailed-tutorial/"><u>How To Resolve Persistent Cursor Blink - A Detailed Tutorial.</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-huawei-nova-y91-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-vivo-s17-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-motorola-moto-e13-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-honor-90-pro-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-vivo-t2-5g-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-oppo-find-x6-pro-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Oppo Find X6 Pro Location Settings | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-realme-gt-5-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Realme GT 5 Location Settings | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-facebooks-top-10-most-watched-music-moments/"><u>In 2024, Facebook's Top 10 Most-Watched Music Moments</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-vivo-s18-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Vivo S18 Devices | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-xiaomi-redmi-12-5g-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Xiaomi Redmi 12 5G</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-infinix-hot-40-pro-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-a38-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-tecno-pop-8-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-mastering-magic-essential-filters-to-make-your-videos-pop/"><u>In 2024, Mastering Magic  Essential Filters to Make Your Videos Pop</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-role-of-authenticity-checks-in-social-media-posts/"><u>In 2024, The Role of Authenticity Checks in Social Media Posts</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-virtualdub-a-review-and-comparison-of-top-video-editing-software/"><u>In 2024, Virtualdub A Review and Comparison of Top Video Editing Software</u></a></li>
</ul></div>
