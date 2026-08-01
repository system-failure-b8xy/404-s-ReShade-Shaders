# 404's ReShade Shaders
Download ReShade [here](https://reshade.me/#download)
This is where you'll find *my* ReShade shaders I made for some of the various games I play.

Currently, the games I made shaders for are:
1. Poppy Playtime (Chapter 1)
2. Slime Rancher 1
3. Scrap Mechanic

## Poppy Playtime Shaders
- LiDAR
- True Darkness with Flashlight

## Slime Rancher 1 Shaders
- LiDAR
- Stylized

## Scrap Mechanic Shaders
- Stylized

## Shader Mechanics
**True Darkness with Flashlight:**
- Press 'F' to toggle the flashlight.

**Stylized:**
- Press 'Z' to toggle zoom.

## Important Info
I'm not sure how well it would relay in the shader files, but, for Slime Rancher and Poppy Playtime's shaders, I have made it to where the effect does not happen on most UI elements, like the pause screen or the hotbar. If it doesn't happen for you, you need the 'Reshade Effect Shader Toggler' addon for ReShade, and, through it, you may need to select the parts of the screen where the UI is when you have a UI open. You don't need to *draw* where the UI is, you simply just need to go through the settings for the addon and select each element that *only* has the UI.

Beecause of that, the shader for Scrap Mechanic does *not* have that anti-UI setting, as, for some reason, Scrap Mechanic has most UI elements in both screen-space *and* world-space. For example, when I was trying to fetch the UI of the Craftbot, no elements *only* had the Craftbot UI - it always also had the viewport of the world camera, so disabling effects for that element would also make everything else distorted since it also effected the world. So, sorry if the UI seems a bit over-saturated for you.
