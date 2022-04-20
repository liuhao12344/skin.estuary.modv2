# Skin Estuary MOD V2 for KODI 19 Matrix KN Edition #

## Installation Notes ##

It's strongly recommended to install the skin via the "Kodinerds Repo", as this is the only way to guarantee that additional 
required modules (e.g. the PVR Artwork Module) are also installed. Another advantage is that you get automatic updates when 
you install an addon from a repository and not from ZIP.

To install the Kodinerds repository visit the page "https://repo.kodinerds.net", download the repository zip (red button) 
and install it. After that you can install the skin directly from the repository under "Look & Feel", "Skins".

### File name flagging ###
If you want to use special flags like HDR or Dolby Vision or special 3D formats you have to name your files with proper tags, 
preferably before the file extension: 

| 3D with <br> stereoscopic detection |           MVC codec            |          Side by Side          |         Top and Bottom         |    HDR Files<sup>*</sup>     |            HDR+ Files            |       Dolby Vision<sup>*</sup>       |
|:-----------------------------------:|:------------------------------:|:------------------------------:|:------------------------------:|:----------------------------:|:--------------------------------:|:------------------------------------:|
|     ![](resources/flags/3d.png)     | ![](resources/flags/3dmvc.png) | ![](resources/flags/3dsbs.png) | ![](resources/flags/3dtab.png) | ![](resources/flags/hdr.png) | ![](resources/flags/hdrplus.png) | ![](resources/flags/dolbyvision.png) | 
|             no tagging              |             3d.mvc             |             3d.sbs             |             3d.tab             |        .hdr., .10bit.        |        .hdrplus., .12bit.        |     .dv., .dovi., .dolbyvision.      |

<sup>*</sup>Will be detected in Kodi Nexus and up and don't need filename tagging.


The HDR type recognition by filename will be removed if Kodi detects the HDR type itself properly.

### Animated Artwork ###

As the setup of animated artwork was done by skinhelper addon (which was removed from skin) the skin itself has now taken 
the management of those artwork. Animated artwork has some limitations (see Kodi Wiki: https://kodi.wiki/view/Artwork_types#Animated_Artwork). 
To get this feature work properly, you have to assign a folder within the skin settings, which contains all the artwork. This 
folder **must** be a folder of your local filesystem. Also you can use network share, which  **must** be mounted to a local mountpoint.
Put all your artwork into this folder. Subfolders are allowed (without nesting). 

If you navigate in your movie library, you'll have a new entry now to (re)assign animated Artwork in the context menu. The skin
supports animated poster only.

![](resources/setup_ap.png)

### 4.0.0+nexus ###
- .0
  * Player.Cutlist (deprecated) changed to Player.Editlist
  * Cut & Scene Markers added
  * update player processinfo (video scan type progressiv/interlaced)
  * Show/hide button for passwords in keyboard added
  * Default color picker dialog added
  * Introducing DefaultColorSettingsButton
  * Skinhelper Colorpicker from optional addons list removed
  

### 3.4.0+nexus ###
- .12
  * fixed incorrect poster overlays in episode view
  * some icons added
  * Media flag gap closed if video codec is missing
  * Background pattern added
  * fixed missing content path for movie genres

  
### Screenshots ###

![PVR Info](resources/screenshots/screenshot_1.png)![Embuary Info](resources/screenshots/screenshot_2.png)
![Music Visualization](resources/screenshots/screenshot_3.png)![PVR OSD](resources/screenshots/screenshot_4.png)
![TV Widget](resources/screenshots/screenshot_5.png)![Video OSD](resources/screenshots/screenshot_6.png)
![Embuary localized Infos](resources/screenshots/screenshot_7.png)
![New channel View](resources/screenshots/screenshot_8.png)
![Improved OSD](resources/screenshots/screenshot_9.png)
![simplified OSD](resources/screenshots/screenshot_10.png)
![colored flags](resources/screenshots/screenshot_11.png)
