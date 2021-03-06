## Export Layer for Android

A Javascript for Adobe Photoshop, that exports the currently selected layer
to PNG files appropriate for use as Android 'drawable' assets.

This script started as the 'Export for iOS' script, found at <http://pastebin.com/12dHWYm8>, 
and originally authored by Daniel Wood ( twitter: @loadedwino )

I modified the iOS script to instead export the appropriate image sizes for Android.
   
This script is intended to be used on a photoshop document containing _mdpi_ artwork for Android. It will resize, trim and save the selected layer or group, into a 
directory you select using the layer name (normalised) for the file name. There are a  
couple of resizing options you can select such as the
resizing method and whether to scale styles or not. It does not alter your original
document in any way.

Images are saved to _drawable-mdpi_, _drawable-hdpi_, _drawable-xhdpi_ and _drawable-xxhdpi_ 
directories under the selected output directory. If these directories do not exist, 
the script will create them.
 
Original 'license':
> Feel free to share/reuse/modify to your heart's content. 
> Attribution would be nice but is not required.

To install this script, copy it to your Photoshop installation directory's 
Presets/Scripts directory, and then re-start Photoshop if it is running.

To run the script, select the layer that you want to export, and then choose the
Export Layer for Android option from PhotoShop's File -> Scripts menu.


## Changelog and Contributors

### V1.4 
 - Added an option to specify also the desired width (in px) for the selected density.
 
### V1.3
 - Merged branches
 
### V 1.*
 - by Brian Lee (GitHub: https://github.com/tigerpenguin, Twitter: @tig3rpenguin)
   - Add XXXHDPI
   
### V 1.*
 - by Aaron Bonham - @abonham
   - Add the ability to choose between export all layers or just active
   - Add toggle for trim whitespace
 
### V 1.* 
 - Modified by Julien Quéré (@juli1quere, http://sinplicity.fr)
   - Add the ability to specify the source file density,
   - Add XXHDPI,
   - Add the "automatic" option for the resize method.
 
### V 1.0 Author: Rich Freedman (greybeardedgeek.net)
GitHub: https://github.com/rfreedman
Twitter: @greybeardedgeek
 
This script started as the 'Export for iOS' script, found at http://pastebin.com/12dHWYm8, and originally authored by Daniel Wood ( twitter: @loadedwino ), Rich Freedman modified the iOS script to instead export the appropriate image sizes for Android.
