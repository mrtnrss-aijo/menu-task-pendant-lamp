# MENU Task Pendant Lamp

A small web page to control a MENU Task Pendant lamp over Bluetooth.

MENU's original lamp app has been decommissioned. MENU was taken over by Audo Copenhagen, which does not support the old app. This page replaces it.

**Open it:** https://mrtnrss-aijo.github.io/menu-task-pendant-lamp/

## Features

- Switch the lamp on and off
- Set brightness (1–100 %)
- Set colour temperature (2700–4000 K, warm to cool)
- One-tap Default setting (50 % / 2700 K)
- Optionally remember the lamp password on each device

## Works on

| Device | Browser |
| --- | --- |
| Laptop | Chrome or Edge |
| Android phone | Chrome |
| iPhone | Bluefy, a free app from the App Store (Safari does not support Bluetooth for web pages) |

## How to use

1. Open the page and enter the lamp password.
2. Tap **Connect** and pick the lamp in the list.
3. Use the controls. Tap **Disconnect** when you are done.

Only one device can be connected to the lamp at a time. If the lamp does not show up, disconnect or close the page on the other device first.

The wall switch keeps working as normal. The lamp remembers the last setting, so it comes back that way when switched on at the wall.

## Notes

- Everything runs in your browser. The page talks to the lamp directly over Bluetooth; nothing is sent over the internet.
- This page is set up for one specific lamp. Using it with another lamp needs a small change to the lamp details at the top of the code.
- Not affiliated with MENU or Audo Copenhagen.
