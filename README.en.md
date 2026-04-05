# MC-Skin

A Userscript that adds a Minecraft character to web pages.

Add a Minecraft character to any website. The character follows your touch or mouse movements. It responds to clicks, mouse wheel scrolling, and typing, playing corresponding animations. Additionally, after 5 minutes of inactivity on the page, the character will sneak and wiggle.

**<span style="color:red">When using the script for the first time, you need to upload a skin file manually.</span>**

The script supports various configurable options via the script menu. Below are the adjustable settings:

1. **Adjust Position**: Click **Move** to drag the character. Then click **Finish Move** to exit moving mode. The position is set as a percentage of the page width/height, so it should theoretically support both landscape and portrait orientation changes.
2. **Adjust Opacity**: Click **Adjust Opacity** to open the opacity slider. Drag the slider to change the character's transparency.
3. **Change Skin**: Click **Change Skin** to open the skin selection dialog. You can click the upload button to pick an image file, drag and drop an image directly onto the upload button (the button turns into a plus sign), or enter a legitimate Minecraft ID to fetch the skin.
4. All the above settings only apply to the current webpage and reset after a refresh. To save them permanently across all pages, click **Save Current Settings**.
5. To reset custom settings to defaults, click **Reset Current Settings**. After resetting, already open pages need to be refreshed for the changes to take effect.
6. Option to show the character in fullscreen mode (disabled by default). When enabled, the character will appear while watching videos or playing games in fullscreen.
7. **Mouse Follow Mode**: Choose between Java Edition mode and Bedrock Edition mode (Bedrock is default). Differences:
   - **Bedrock mode**: Only the head follows the mouse. The body tilts toward the vertical central axis of the screen based on position. Lighting simulates Bedrock Edition (directional light).
   - **Java mode**: The entire body follows the mouse. Lighting simulates Java Edition (hemisphere light).

Thanks to:

Open source projects [skinview3d](https://github.com/bs-community/skinview3d) [three.js](https://github.com/mrdoob/three.js/)

Source code repository:

[MC Skin](https://github.com/undefined303/MC-Skin)

Welcome stars, issues, and pull requests.

If you encounter bugs or have suggestions, feel free to raise them, but due to limited personal ability, they may not be addressed.

Video tutorial (Chinese language only): [【MC × Browser – Let the block man cross into the browser】](https://b23.tv/WdJ502T)
