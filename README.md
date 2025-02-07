
<p align="center">
    <h1 align="center">Asev's Windows Desktop 🌇</h2>
</p>

<p align="center">How I customize my Windows 11 desktop 🌸</p>

![](https://github.com/lunar-os/windowsdesktop3/blob/main/asdas.png)

## Things I used

- [Wallpaper](https://github.com/lunar-os/windowsdesktop3/blob/main/wallpaper.png) (edited from unsplash)
- [Taskbar Font](https://fonts.google.com/specimen/Poppins) | [Windows Font](https://fonts.google.com/specimen/Mulish) | [Terminal font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/JetBrainsMono.zip)
- Windows msstyles theme: [by niivu](https://www.deviantart.com/niivu/art/pi11z-for-Windows-11-1084568949) ([Guide](https://www.deviantart.com/niivu/art/How-to-install-Windows-10-or-11-Themes-708835586) to install)
- [Zen browser Theme](https://github.com/lunar-os/ZenCss)
- [Right Click menu](https://nilesoft.org/download) | My [theme](https://github.com/lunar-os/windowsdesktop3/blob/main/theme.nss)
- Window Borders https://github.com/lukeyou05/tacky-borders | 
<details>
<summary>tacky-borders config (click to expand)</summary>

```
# Customize global config options
global:
  border_width: 2 # Width of the border
  border_offset: -1 # How close the border is to the window edges
  border_radius: -1 # Radius of the corners. Leave it at -1 to let tacky-borders handle the radius or set your own custom value.

  active_color:
    colors: ["#cd7271", "#5a606e"]
    direction:
      start: [0.0, 0.0] # [0.0, 0.0] is the top left corner (windows api is weird like that)
      end: [1.0, 1.0] # [1.0, 1.0] is the bottom right corner
  #active_color: "#7F7FD5"

  inactive_color:
    colors: ["#cd7271", "#5a606e"]
    direction:
      start: [1.0, 0.3] # [0.0, 0.0] is the top left corner (windows api is weird like that)
      end: [0.0, 0.7] # [1.0, 1.0] is the bottom right corner
  #inactive_color: "#575660" # Color of unfocused windows. Currently supports a hex code like "#ffffff" or "accent" (and now gradients!)

  initialize_delay: 50 # I reduce the delay here because of the fade animation which takes some time itself
  unminimize_delay: 50

  animations:
    fps: 15  # Reduced from 30 to slow down the animation
    active:
      - type: ReverseSpiral
        duration: 1800
        easing: Linear
      - type: Fade
        duration: 200
        easing: EaseInOutQuad
    inactive:
      - type: Spiral
        duration: 1800
        easing: Linear
      - type: Fade
        duration: 200
        easing: EaseInOutQuad

# Customize config options on a per-app basis
window_rules:
  - match: "Class"
    name: "Windows.UI.Core.CoreWindow"
    enabled: false

  - match: "Class"
    name: "XamlExplorerHostIslandWindow"
    enabled: false

  - match: "Title"
    name: "Flow.Launcher"
    enabled: false

  - match: "Title"
    name: "Zebar"
    enabled: false

  - match: "Title"
    name: "keyviz"
    enabled: false
  # EXAMPLE CONFIGURATION:
  # - match: "Class"               # Currently supports "Class" or "Title"
  #   name: "MozillaWindowClass"   # Name of the class or title
  #   strategy: "Equals"           # Optional. Currently supports "Equals", "Contains", or "Regex". Defaults to "Equals"
  #   border_width: 10             # The next few options are all optional and default to global config if nothing is specified
  #   border_radius: -10
  #   border_offset: -10
  #   active_color: "#ffffff"
  #   inactive_color: "#000000"
  #   enabled: true                # Optional. Enables or disables the border. Defaults to true. Note: you can't forcibly enable borders yet

```
</details>


## Windhawk
### Windhawk is for all the taskbar/start menu customizations along with many other things. You can get it from [Windhawk.net](https://windhawk.net/)
Mods used: 
- Windows 11 Taskbar Styler | [My config](https://github.com/lunar-os/windowsdesktop3/blob/main/WindhawkConfigs/Taskbar) (Volume in top right currently isn't dynamic)
- Taskbar on top for Windows 11
- Windows 11 Notification Center Styler | [My config](https://github.com/lunar-os/windowsdesktop3/blob/main/WindhawkConfigs/Notification)
- Taskbar Volume Control
- Taskbar Labels for Windows 11 | [My config](https://github.com/lunar-os/windowsdesktop3/blob/main/WindhawkConfigs/Labels)
- Taskbar height and icon size | Icon size:20 / Taskbar height:38 / Taskbar button width:36
- Taskbar Clock Customization | [My config](https://github.com/lunar-os/windowsdesktop3/blob/main/WindhawkConfigs/Clock)
- Windows 11 Explorer Styler | [Mod creators install guide on Windhawk Discord server](https://discord.com/channels/923944342991818753/1317578806143484084/1317578806143484084) | [Windhawk mod code](https://github.com/m417z/my-windhawk-mods/blob/e6418aee969c0e2d181dd87f3a79af6b3543550f/mods/windows-11-file-explorer-styler.wh.cpp) | [My Config](https://github.com/lunar-os/windowsdesktop3/blob/main/WindhawkConfigs/Explorer)
- Disable grouping on the taskbar

## Extras

- [Icon pack by Niivu](https://github.com/lunar-os/windowsdesktop3/blob/main/7tsp%20Pi11z.7z)
- Taskbar [Icons](https://tablericons.com/)
- [Screenshot tool](https://getsharex.com/)
- [Spotlight Search](https://www.flowlauncher.com/) | With the [theme](https://github.com/abhidahal/onsetGlaze.flow)
- [AltSnap](https://github.com/RamonUnch/AltSnap) for window management
- [Cursor](https://www.deviantart.com/jepricreations/art/Windows-11-Cursors-Concept-HDPI-890672103)
- Discord themed with [Vencord](https://vencord.dev/)
- Spotify themed with [Spicetify](https://spicetify.app/)

