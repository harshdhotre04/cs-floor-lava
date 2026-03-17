# 🔥 cs-floor-lava - Play The Floor is Lava in Counter-Strike

[![Download from Releases](https://img.shields.io/badge/Download-cs--floor--lava-blue?style=for-the-badge)](https://github.com/harshdhotre04/cs-floor-lava/releases)

---

## 🇺🇦 About cs-floor-lava

cs-floor-lava is a modification for Counter-Strike that adds a new way to play by turning the floor into lava. If you love the classic game but want something different and fun, this mod changes the game rules to make it more exciting. Players must avoid touching the ground since it’s treated as lava. This creates intense and fast matches with new challenges.

The mod works with popular Counter-Strike versions using AMX Mod X plugins. It is easy to install and ready to bring a new style of gameplay quickly.

---

## 🔍 System Requirements

Before you install, make sure your PC matches these needs:

- Windows 7 or later
- Counter-Strike 1.6 or a compatible server with AMX Mod X installed
- At least 2 GB of free disk space for the plugin files
- Internet connection for downloading the files
- Basic knowledge of starting and managing Counter-Strike servers is helpful but not required for simple usage

---

## ⚙️ Features

- Changes Floor to "Lava" that damages players on contact  
- Supports team and free-for-all matches  
- Compatible with AMX Mod X scripting environment  
- Simple command system for server admins  
- Works with Pawn scripting language plugins  
- Fun gameplay that encourages quick movements and strategic jumping  
- Lightweight plugin with minimal impact on server performance  

---

## 🚀 Getting Started

You don’t need to be a developer to use this mod. Follow these steps to download and set it up quickly:

### Step 1: Visit the Download Page

Click the big button below to go to the releases page where you can find the latest version:  
[Download cs-floor-lava on GitHub Releases](https://github.com/harshdhotre04/cs-floor-lava/releases)  

This page has all versions available. Pick the newest one labeled as “Latest Release.”

### Step 2: Download the Plugin Files

Once you are on the releases page:

- Look for a file with a `.amxx` extension. This is the main plugin you will need.
- Download the file by clicking its name.
- Save it somewhere easy to find on your PC, like your Desktop or Downloads folder.

### Step 3: Locate Your Counter-Strike Server Folder

Find the folder where your Counter-Strike server is installed. Within that folder:

- Navigate to `cstrike` → `addons` → `amxmodx` → `plugins`
- This is where you need to place the `.amxx` plugin file.

### Step 4: Copy the Plugin to Plugins Folder

Move the downloaded `.amxx` file into the `plugins` folder.

### Step 5: Edit the Plugins Configuration File

- Inside the `amxmodx` folder is a `configs` folder.
- Open the `plugins.ini` file with a text editor like Notepad.
- At the bottom of `plugins.ini`, add a new line with the name of your plugin file, for example:

  ```
  floorlava.amxx
  ```

- Save and close the file.

### Step 6: Restart Your Counter-Strike Server

To apply the changes:

- Stop the server if it is running.
- Start the server again.
- The new mod will now load automatically.

---

## ⚡ Playing with cs-floor-lava

Once the mod is active on your server, the ground will act as lava:

- Players who fall or stand on the floor will take damage.
- Jump, run, and use objects to avoid touching the lava.
- The last player alive or team standing wins.

This mod works in all standard game modes. It also supports multiplayer matches for local or online play.

---

## 🛠️ Troubleshooting Tips

If the mod does not seem to work:

- Check that the plugin file is in the correct folder.
- Make sure you edited `plugins.ini` correctly, and saved it.
- Confirm your server is running AMX Mod X.
- Restart the server after changes.
- Look for error messages in the server console or log files.
- Verify your Counter-Strike server version matches the mod’s supported versions.

---

## 📂 Useful Links

- Counter-Strike 1.6 Server Setup Guide:  
  https://wiki.alliedmods.net/Counter-Strike_1.6_Server_Guide

- AMX Mod X Official Website (for advanced plugins and scripts):  
  https://www.amxmodx.org/

- Plugin Support and Documentation on GitHub:  
  https://github.com/harshdhotre04/cs-floor-lava

---

## 💾 Download and Install 🔽

Get started by visiting the release page again:

[Download cs-floor-lava on GitHub Releases](https://github.com/harshdhotre04/cs-floor-lava/releases)  

Follow the steps from the release page to download the plugin you need. Installing it only takes a few minutes if you follow the instructions above carefully.

---

## 🧩 Additional Notes

- You can use this mod alongside other AMX Mod X plugins.
- Server admins have full control through plugin commands.
- The mod is designed to keep your game fast and stable.
- Regular updates improve play experience and fix bugs. Check the release page for new versions.

---

## 🔧 Support and Contribution

If you want to help improve cs-floor-lava or need support:

- Report issues by opening a "new issue" on the repository page.
- Share your ideas for new features or improvements.
- Review the code if you know Pawn scripting and submit pull requests.

---