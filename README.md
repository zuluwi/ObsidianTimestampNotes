## Obsidian Timestamp Notes


### Use Case
Hello Obsidian users! Like all of you, I love using Obsidian for taking notes. My usual workflow is a video in my browser on one side of my screen while I jot down notes in Obsidian on the other side. While Obsidian itself is a great notetaking tool, I found this setup quite lacking. When reviewing my notes, it would often take me a long time to find the section of the video the note came from and I found it annoying constantly having to switch between my browser and Obsidian. 

## Solution
This plugin solves this issue by allowing you to:
- Open up a video player in Obsidian's sidebar
- Insert timestamps with a hotkey
- Select timestamps to navigate to that place in the video

## Setup 
- Download and enable the plugin
- Set the hotkeys for
  - Opening the video player (my default is cmnd-shift-y)
  - Opening a local video (my defauly is cmnd-shift-l)
  - Inserting timestamps (my default is cmnd-y)
  - Playing/pausing video (my default is cntrl-space)
  - Seeking forward/back (my default is cntrl-arrows)
- Set options for
  - Colors of the url, url text, timestamp button, and timestamp text
  - Title that is pasted when 'Open Video Player' hotkey is used
  - How far you want to seek forward/back

## Usage
- Copy to clipboard or highlight a video url and use the 'Open Video Player' hotkey or press your designated hotkey to select a local video/audio file to play
- Jot down notes and anytime you want to insert a timestamp, press the registered hotkey
- Toggle pausing/playing the video by using hotkey (my default is option space)
- Open videos at the timestamp you left off on (this is reset if plugin is disabled)
- Close the player by right-clicking the icon above the video player and selecting close 

## Valid Video Players
This plugin should work with:
- youtube
- vimeo
- facebook
- soundcloud
- wistia	
- mixcloud
- dailymotion
- twitch
- local videos/audios
- bilibili

## Demo

https://user-images.githubusercontent.com/39292521/167230491-f5439a62-a3f7-445c-a208-839c804953d7.mov


## Known Issues
1. Inserting timestamps into a bulleted section does not work. Unfortunately, code-blocks cannot be in-line with text. Make sure to press enter/insert the timestamp on a new line.
2. If you decide to change the colors of your buttons/text, any old buttons/text will not update with the new colors until you reload the app. You can also click the '<>' when hovering over the code-block and it will refresh with the new colors.
3. If your timestamp/video button dont work, simply switch between live-editing and viewing modes.



## Other Authors
This plugin uses the react-player npm package: https://www.npmjs.com/package/react-player.
