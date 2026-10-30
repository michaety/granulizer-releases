# Granulizer

**A granular delay plugin for Windows, by Hevin Design.**
It chops sound into tiny grains and scatters them across a delay you can shape by hand. Run your music through it, or drop a sound file straight into it.

---

## Download

### [**⬇ Download Granulizer-Setup.exe**](https://github.com/michaety/granulizer-releases/releases/latest/download/Granulizer-Setup.exe)

That link always gives you the newest version.

For Windows 10 or 11 (64-bit) and any music program that uses **VST3 plugins** (FL Studio, Ableton Live, Reaper, Cubase, Studio One…).

---

## Install (about 2 minutes)

1. **Run `Granulizer-Setup.exe`.**
   Windows may show a blue box saying **"Windows protected your PC"**. That's normal for new small programs. Click **More info**, then **Run anyway**.
2. Click **Yes** when Windows asks for permission, then **Next → Install → Finish**.
   If your music program is open, the installer will ask to close it. Say yes.
3. **Open your music program and make it find the new plugin:**

   | Program | What to do |
   |---|---|
   | **FL Studio** | *Options → Manage plugins*, tick **Verify plugins**, click **Find installed plugins**. |
   | **Ableton Live** | *Preferences → Plug-Ins*, switch on **Use VST3 Plug-In System Folders**, click **Rescan**. |
   | Other programs | Look for "rescan plugins" in the plugin settings. |

4. **Add Granulizer to a track as an *effect*.**
   - FL Studio: click an empty slot on a Mixer track and pick **Granulizer**.
   - Ableton: drag **Granulizer** from *Plug-Ins* onto an audio track.

---

## Your first sound

- **Run something through it:** play a loop on the track. Turn **Mix** to about half.
- **Or drop a file in:** drag a `.wav`, `.aiff`, `.flac`, `.ogg` or `.mp3` file onto Granulizer's window. It plays that instead (no track needed).
- **Add echoes:** double-click anywhere in the big picture to add a delay. Drag it left or right to move it, up or down to pan it, and drag its edges to make it wider.
- **Freeze** (top right) holds the sound so you can play with it.
- Try the presets with the **‹ ›** arrows at the top.

---

## Updates

You don't need to come back here. When a new version is ready, a bar appears at the top of Granulizer's window. Click **Download update**, then **Install**. It installs when you next close your music program.
(Updates are checked at most twice a day. You can switch that off at the bottom of the window.)

---

## If something's wrong

| Problem | Fix |
|---|---|
| **Granulizer isn't in my plugin list** | Rescan plugins (step 3 above). In Ableton make sure *Use VST3 Plug-In System Folders* is on. |
| **The window shows plain sliders instead of the picture** | Your PC is missing Microsoft's *WebView2*. Reinstalling with the installer fetches it automatically, or search "WebView2 Runtime" on microsoft.com. |
| **No sound change** | Check **Mix** isn't at 0%, and that Granulizer is on a track with sound (or that a file has been dropped in). |
| **Windows blocks the installer** | Click **More info → Run anyway**. If the file was downloaded from a message app, right-click it → *Properties* → tick **Unblock** first. |

To remove Granulizer: *Windows Settings → Apps → Granulizer (VST3 plugin) → Uninstall*.

---

*© Hevin Design*
