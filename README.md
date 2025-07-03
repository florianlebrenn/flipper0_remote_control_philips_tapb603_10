# Flipper Zero – Automated Remote Control for Philips TAPB603/10

Some Philips soundbars, such as the **TAPB603/10**, require the command to be sent **twice** with a pause in between to toggle power reliably. A simple `.ir` file is not sufficient for this use case.

This guide explains how to automate this sequence on your **Flipper Zero** using the **Cross Remote** app.

---

## Requirements

- **Flipper Zero** with compatible firmware (1.3.4)
- **Cross Remote** app installed from [Flipper Lab](https://lab.flipper.net/apps/xremote)
- One or more `.xr` files containing the appropriate IR sequence

---

## Installing Cross Remote

1. Open the **Lab** app on your Flipper Zero or visit [lab.flipper.net/apps/xremote](https://lab.flipper.net/apps/xremote).
2. Install the **Cross Remote** application.

---

## Preparing the Files

1. **Copy all `*.xr` files** into the following folder on your Flipper Zero’s SD card: `SD Card/apps_data/xremote`

## Running the Sequence

1. On your Flipper Zero, navigate to: `Apps > Infrared > Cross Remote > "Run Saved Command"`

You should see imported commands, just select one of them.
