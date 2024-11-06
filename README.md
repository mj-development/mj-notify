# MJ Notify - QBCore Notification UI

A sleek, customizable notification UI for FiveM (QBCore), designed to enhance your server with clear, professional notifications. MJ Notify is free and easy to integrate into any server!

![MJ Notify](images/preview1.png)

## Features
- **Customizable** notification styles
- **Modern UI** for better readability
- **Free** to download and integrate!

## Preview

![Preview of Notifications](images/preview2.png)

### Live Demo
![Demo](images/demo.gif)

## Installation

1. Download the repository and place it in your FiveM server resources folder.
2. Add `start mj-notify` to your `server.cfg`.
3. Customize the notifications in `config.lua` as per your needs.

## Usage

```lua
-- Sample code to trigger a notification
TriggerEvent('mj-notify:showNotification', 'Your message here', 'info')
