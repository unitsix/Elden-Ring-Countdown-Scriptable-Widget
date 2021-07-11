# Elden-Ring-Countdown-Scriptable-Widget
This is a simple Elden Ring countdown widget for [Scriptable](https://scriptable.app). 

<p align="center">
  <img src="https://github.com/unitsix/Elden-Ring-Countdown-Scriptable-Widget/blob/main/Cover%20Image.jpg?raw=true" alt="Cover image" style="max-width: 300px;"/>
</p>

## Instal

[Download](https://github.com/unitsix/Elden-Ring-Countdown-Scriptable-Widget/archive/refs/heads/main.zip) and extract the content of this repository into the Scriptable folder located in your iCloud Drive.

1. Your Scriptable folder structure should look something like this:

```
iCloud Drive/
 ├─ Scriptable/
 │  ├─ Elden Ring Countdown.js
 │  ├─ Elden Ring Countdown/
```

2. Launch Scriptable and make sure that Elden Ring Countdown is listed in the Scripts view.

3. Run the script and you should see a preview of the Medium-sized widget.

4. Optionally save some images to use as backgrounds, see below `Using stored images` and change any of the config to suit yourself.

5. Return to your home screen and add a Medium Scriptable widget.

6. Edit the Scriptable widget and choose Elden Ring Countdown as the Script. You may even want to, set "When Interacting" to open `https://www.reddit.com/r/Eldenring/`.

## Config

Setting | Description
--- | ---
countDownDate | The time and date we become tarnished
isTitleTextEnabled | Want to see the title text within the widget?
titleString | The text copy shown as title
daysString | The suffix text of wait within the widget when there are days left remaining
hoursString | The suffix text of wait within the widget when there are hours left remaining
minsString | The suffix text of wait within the widget when there are only mins left remaining
timeUpString |  When the time is up and there is nothing to count down to, text within widget
isNotificationEnabled | Want a notification when its out?
notificationTitleString | The title of the notification
notificationBodyString | The body of the notification
storedImageNames | Names of saved image/s in the iCloud directory, see below

### Using stored images
Save image/s in the iCloud directory (can use the Files app) then use (copy/paste) the file name into storedImageNames array. If you cannot see the extension name in Files app; click the (i) info icon on the file.

eg;
```
const storedImageName = [
  "cool_elden_ring_background.png",
  "an_awesome_image_of_the_valkyrie.jpg"
]
```
where your file structure looks like;
```
iCloud Drive/
 ├─ Scriptable/
 │  ├─ Elden Ring Countdown.js
 │  ├─ Elden Ring Countdown/
 │  │  ├─ cool_elden_ring_background.png
 │  │  ├─ an_awesome_image_of_the_valkyrie.jpg
```

## About this project

This script is a fun little project to try out Scriptable and count down to the next best game.

If you like this project, please throw a star and/or follow me on github.
