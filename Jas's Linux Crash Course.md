Basic explanation, documentation, and showcase of various Linux distros, programs, and tools. Version 1.

# What is Linux?
Linux commonly refers to many things, but at its core, Linux is an open-source, community developed kernel. Think of the kernel like the lower-level brain that makes your operating system run. It contains all the necessary code to make your USB ports work, make your network card run, and do all sorts of hardware-level functions.

Separate from the kernel is what's called "userland", which is what you as the user can interact with on the computer. Generally, when someone is referring to the OS of a computer, they're mainly talking about the userland, which in Windows and MacOS goes hand in hand with their kernels. The Windows kernel is referred to as NT, is entirely enmeshed with the Windows OS, and cannot be changed or removed - same with the MacOS kernel, called Darwin, which is a distant cousin to the Linux kernel.
# What is a Linux Distro?
A Linux distro, short for "distribution", is partially an OS, partially a customization of the OS.
Each and every distro has different programs, looks, and underlying tools, and though it can be easy to get overwhelmed choosing a distro, it's important to take your time and prioritize finding one you like over using the new hot 'thing'.
### Distro "Families"
Linux distros fall into several distinct "family trees", where options in the same tree will share a lot in common compared to others.
The three main groups are Debian-based, Fedora-based, and Arch-based. Both Android and ChromeOS(the OS that runs a Chromebook) are also in their own tree, though have less cross-compatibility with the other Linux-based distros.
### Major Differences
The usual things that differentiate a Linux distro are the package manager, desktop environment, and basic utilities. Generally, Debian-based systems are long-term support focused, Fedora-based systems stay relatively up to date with the stable Linux kernel, and Arch-based systems run on rolling releases - expect updates to be available daily, and the occasional tinkering session.
##### Package Manager
A package manager is like the app store on your phone. Instead of downloading programs from a random website, many times you can simply fetch the program via your package manager, which will handle installation and deployment for you.
Many distributions also include GUI-based package installers - they do all the command work for you!
**Common Package Managers**
- apt - Used by Debian, Ubuntu, and others in the Debian family
- pacman - Used by Arch-based systems
- RPM - Used by Fedora and other RedHat-related systems
- Flatpak - Cross-distro packaging system that runs programs in partial isolation
- Snap - Canonical's proprietary version of a Flatpak-like system for Ubuntu
- AppImage - Portable application system
##### Desktop Environment
The desktop environment(**DE**) is the graphical part of your OS - the desktop, windows, and other graphical UI parts.
Desktop environments are powered by what is called a "display server" that dictates how elements are displayed. There are two families of display server - X11 and Wayland. X11 featured prominently in the older Linux ecosystem, and Wayland is being transitioned to throughout the mid 2020s by more and more DEs.
**Common Desktop Environments**
- GNOME - Functions similar to the MacOS desktop, with a centered application bar at the bottom and a system menu at the top.
- KDE Plasma - Functions similarly to the Windows desktop, with an application launcher at the bottom left attached to the taskbar. 
- Cinnamon - GNOME-based version of a Windows desktop-like interface.
- LXQT/XFCE - Lightweight DEs intended for use in lower power systems.
There are several more DEs not listed here, including Budgie, Deepin, MATE, and a myriad of non-DE window managers. I won't go into too much detail on tiling window managers, but for more info read up on Niri, Hyprland, i3/sway, and AwesomeWM.
### Debian-based
###### Debian
- 2nd oldest Linux distro
- "Old Man Linux" - Debian maintains stable releases for free for 5 years
- Supports a variety of options for DEs
###### Ubuntu
- Developed by Canonical, a Linux server company
- Commonly certified for use on HP/Dell/Lenovo hardware with official support
- Multiple "flavors", essentially sub-distros catered towards specific use cases or DEs
###### Linux Mint
- Beginner-friendly distro
- Made to work out of the box with no tweaking
- Features Cinnamon DE by default
###### Pop!\_OS
- Ubuntu-based, developed by System76
- Designed for minimal clutter
- Uses COSMIC DE by default - currently under development, previously based on GNOME
###### MX Linux
- Midweight distro, with high stability
- Features XFCE as the default DE
### Fedora-based
###### Fedora
- Yearly release schedule
- Community-developed
- Features KDE Plasma as default DE
###### RedHat Enterprise Linux
- RedHat's Fedora-based distro
- Free for personal use, intended for large deployments and developers
- Features GNOME by default
###### Nobara Linux
- Fedora-based Gaming-focused distro
- Has custom repositories for applications, alongside Fedora packages
- Features customized KDE Plasma as default DE
###### Bazzite
- Fedora-based, gaming-focused, immutable (root files cannot be edited) distro
- Development via discord community - take from that what you will
- Offers both KDE Plasma and GNOME by default
### Arch-based
###### Arch Linux
- Bleeding-edge, rolling release minimalist distro
- Extensive wiki, users intended to frequently reference as needed
- Build-your-own-system - does not have built in configuration tools
###### CachyOS
- Gaming-focused Arch-based distro
- Fully-customized software stack - offers customized packages for optimization
- Installer provides 10+ options for DEs and tiling window managers
###### EndeavourOS
- Simple, preconfigured Arch-based distro
- Good way to dip your toes into Arch without having to jump into the deep end
- Features KDE Plasma by default, but supports many DEs
###### SteamOS
- Gaming-focused, Valve-developed Arch-based distro
- Designed specifically for the Steam Deck, likely to see a release for Steam Machine
- Features KDE Plasma in Desktop Mode
