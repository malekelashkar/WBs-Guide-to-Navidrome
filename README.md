# 🎵 WBs-Guide-to-Navidrome - Simple Music Server Setup

[![Download Latest Release](https://img.shields.io/badge/Download-Navidrome-green?style=for-the-badge&logo=github)](https://github.com/malekelashkar/WBs-Guide-to-Navidrome/releases)

---

## 🎯 What Is This?

This guide helps you set up Navidrome, a music server you can run on your own Windows PC. Navidrome lets you play your music collection from anywhere. You do not need to be a programmer to use this guide. Each step is written in plain language.

You will learn how to:

- Install Navidrome on Windows
- Organize your music files
- Fix music tags for better sorting
- Set up apps to play your music
- Access your music remotely
- Add internet radio stations
- Create smart playlists automatically

This setup is based on proven recommendations from the music server community.

---

## 🛠️ What You Need

Before starting, make sure you have:

- A Windows PC running Windows 10 or 11
- 2 GB of free disk space (more if you have a large music collection)
- A stable internet connection
- Your music collection ready to use (MP3, FLAC, etc.)

No special skills are needed. You only need to follow the steps carefully.

---

## 💾 Step 1: Download and Install Navidrome on Windows

You will first download Navidrome, the music server software.

1. **Go to the release page** by clicking the green button above or visit:  
   https://github.com/malekelashkar/WBs-Guide-to-Navidrome/releases

2. On that page, look for the latest Windows release files. It usually ends with `.exe` or `.zip`.

3. Click to download the Windows installer or zip file.

4. If you downloaded the `.exe` file:
   - Double-click the file to start the installation.
   - Follow the prompts. Choose default options if unsure.
   - Wait for the installer to finish.

5. If you downloaded the `.zip` file:
   - Right-click the `.zip` file and choose "Extract All."
   - Save the extracted folder to a location you will remember, like your Desktop.

6. Open the folder and find `navidrome.exe`. Double-click it to start the server.

Once Navidrome is running, it will open a web page in your default browser showing the server interface.

---

## 🎵 Step 2: Prepare Your Music Library

Navidrome works best when your music files have clear information like artist, album, and track title.

1. Collect all your music files in one folder on your PC.  
2. Your folder can have subfolders to keep artists or albums separate.  
3. You can improve tags using a free app called MusicBrainz Picard. This app helps fix missing or wrong information in music files.

---

## 🏷️ Step 3: Fix Music Tags Using MusicBrainz Picard

Good tags help Navidrome organize your music correctly.

1. Download MusicBrainz Picard from https://picard.musicbrainz.org/downloads/  
2. Install and open Picard on your PC.  
3. Drag your music folder or selected files into Picard.  
4. Click "Scan" to let Picard find matches for your songs.  
5. Review and save the updated tags.

This step makes sure your songs show correct artist names, albums, and genres in Navidrome.

---

## 🎨 Step 4: Fix Genre Tags

Navidrome uses genre tags to sort music. You can clean up genres in Picard:

1. In Picard, select tracks to edit.  
2. Replace unclear or misspelled genres with common terms like Rock, Jazz, Pop, etc.  
3. Save changes to update your files.

Clear genres improve playlist creation and browsing.

---

## 📲 Step 5: Set Up Playback Apps

Navidrome works with many apps on different devices.

- On Windows or Mac, use web browsers to play music from the Navidrome interface.  
- On phones or tablets, install apps like DSub (Android), Dopamine (Windows), or any Subsonic-compatible player.  
- Connect these apps to Navidrome by entering your server’s IP address and login info.

This setup lets you listen to your music anytime on any device.

---

## 🌐 Step 6: Enable Remote Access with Tailscale

To listen to your music when away from home, you need remote access.

1. Install Tailscale on your PC and other devices: https://tailscale.com/download/  
2. Create a free Tailscale account.  
3. Log into Tailscale on all devices.  
4. When Navidrome runs on your PC, it becomes available on your Tailscale network.  
5. Use your device’s Tailscale IP address in playback apps to connect remotely.

Tailscale keeps this connection secure without complicated router setup.

---

## 📻 Step 7: Add Radio Stations

Navidrome allows you to add internet radio to your server.

1. Find URLs of your favorite online radio streams.  
2. Open the Navidrome web interface.  
3. Go to the radio stations section.  
4. Use the “Add Station” button and paste the URL.  
5. Name the station, then save it.

Now you can listen to radio alongside your music library.

---

## 📂 Step 8: Create Smart Playlists

Smart playlists update themselves based on rules you set, like “Recently Added” or “Most Played.”

1. In the Navidrome web interface, navigate to Playlists.  
2. Select “Create Smart Playlist.”  
3. Choose criteria such as genre, date added, or play count.  
4. Save the playlist.

Your playlists update automatically as you add or play music.

---

## 🔄 How to Keep Navidrome Running

- Make sure to keep Navidrome running on your PC to access music.  
- You can close the server by stopping the `navidrome.exe` process or closing its window.

---

## 🗂️ More Resources

- Visit the official Navidrome documentation for advanced setup options: https://www.navidrome.org/docs/  
- Join online communities for help and tips.

---

[![Download Navidrome Now](https://img.shields.io/badge/Download-Now-blue?style=for-the-badge&logo=github)](https://github.com/malekelashkar/WBs-Guide-to-Navidrome/releases)