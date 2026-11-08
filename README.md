# BIG Studio

**A streaming and recording studio for Windows, with everything a streamer needs built in.**
Multistreaming, vertical video, chat, alerts, clips and short-form editing all live in one
app. You don't need plugins, browser sources or a stack of helper apps.

> 🧪 **Private tester build.** Thanks for helping! If something breaks, BIG Studio saves a
> report by itself. See [Reporting bugs](#reporting-bugs).

---

## Download

1. Open **[Releases](../../releases/latest)** and download `BIG-Studio-Setup-<version>.exe`.
2. Run it. If Windows says *"Windows protected your PC"*, click **More info**, then
   **Run anyway**. (The app isn't code-signed yet.)
3. That's it. Python, FFmpeg and everything else is included.

**Updates come to you.** When a new version is out, a bar at the top of BIG Studio offers it.
Click **Update now** and it downloads, installs and reopens by itself, keeping all your
settings, scenes and logins.

---

## Why BIG Studio instead of OBS?

OBS is a great, flexible broadcasting tool. A typical OBS setup, though, also needs plugins, a
third-party alert service, browser-source overlays, a chat app and a video editor. BIG Studio
builds all of that in, so it works the moment you log in.

| | **BIG Studio** | **Typical OBS setup** |
|---|---|---|
| Stream to Twitch, Kick, YouTube and custom servers **at the same time** | ✅ Built in. It encodes once, so going to more platforms barely costs extra | Needs a multi-output plugin |
| **Landscape + vertical (9:16)** streams at the same time | ✅ Built in, with a separate vertical layout | Needs a plugin |
| **Twitch + Kick chat** in one window, and on stream | ✅ Built in, one combined chat | Browser docks or a third-party overlay |
| **Alerts** (follows, subs, gifted subs, raids, Kicks) | ✅ Drawn by BIG Studio itself, with your own styles and sounds | Usually a third-party web service |
| **Viewer count** overlay across platforms | ✅ Built in | Third-party overlay |
| **Title and category** for every platform from one window | ✅ Built in | Usually set on each platform's website |
| **Automatic highlights**: finds hype moments while you stream | ✅ Built in | Not available |
| **Voice command** "clip that" | ✅ Built in | Not available |
| **Short-form editor** for TikTok, Shorts and Reels | ✅ Built in | A separate video editor |
| **Twitch clips** browser, downloads and "make a short" | ✅ Built in | Twitch's website |
| **Smart Performance Mode** that watches your game's FPS | ✅ Built in | Not available |
| **Crash reports** you can just send | ✅ Automatic, with keys and passwords removed | Log files |

---

## Everything it does

### 🎥 Scenes and sources
- Screens, windows, webcams, images, videos, text and colors, all freely movable and resizable
- **Scene templates and overlay presets** to get a good-looking layout in one click
- **Scene transitions**: fade, cut, slide, zoom and swipe
- **Chroma key** (green screen) with a live preview and "pick color from video"
- **Crop** any source
- **Presets** that save and share your whole setup (scenes, plugins, alerts). Logins are never included.

### 📡 Streaming and recording
- **Multistream** to Twitch, Kick, YouTube and custom RTMP servers at once. If one platform
  drops, the others keep going, and it reconnects by itself.
- **Dual format**: a landscape and a vertical stream at the same time, each with its own layout
- **GPU-accelerated** screen capture and encoding to keep the load on your game low
- **Record** while streaming, using the same encode for no extra cost
- **Replay buffer clips**: save the last 30 seconds (or more) with one click or hotkey, in
  landscape and vertical
- **Live session log** for every stream, to see exactly what happened if it went badly

### 🎙️ Audio
- Mixer for mic and desktop audio, with meters, mute and mono
- **Per-app audio capture**: put just Spotify or just your game on stream
- **Voice effects**: low cut, noise gate, compressor, EQ and limiter, for a clean voice with no extra software
- Monitoring through your headphones

### 💬 Chat, alerts and overlays
- **One combined chat** for Twitch and Kick, with badges, colors and emotes. Read and reply right in BIG Studio.
- **Chat overlay** on stream with your own font, colors, animations and platform icons
- **Stream alerts** for follows, subs, resubs, gifted subs, raids and hosts, Kicks and more,
  each with its own text, color, sound and duration
- **Viewer count** overlay: the total, per platform, or both
- **Stream title and category** for every platform from one window, with game search

### ✂️ Clips and short-form
- **Creator Dashboard** with your highlights, clips and shorts in one place
- **Automatic highlight detection** from audio spikes, chat bursts and big events (subs, raids…)
- **"Clip that"** voice command, which also makes a real Twitch clip and a stream marker
- **Twitch clips**: browse your most viewed, download them, or turn one into a short
- **Short editor**: 1080×1920 export for TikTok, YouTube Shorts and Reels, with crop,
  camera + game split, or blurred-background layouts and safe-zone guides

### ⚡ Performance
- **Smart Performance Mode** (Quality, Balanced, Gaming): detects when you're in a game, shows
  its FPS and frame times, and turns down BIG Studio's own preview and animations to protect
  your game. It never touches your stream's quality.
- **Diagnostics page** with live, measured numbers for every part of the pipeline
- **Global hotkeys** that work while your game has focus

### 🎨 Your studio, your way
- **Dockable Live Studio**: drag every panel anywhere, pop panels out, and save named layouts
- **Grid snapping** so windows line up easily
- **Compact layout** that switches on by itself when the window is small
- **Themes**: Classic, Dark and Light, plus your own colors, a sidebar picture and your own logo

### 🛡️ Safety
- Stream keys and logins are **encrypted** on your PC (Windows DPAPI) and never shown
- Twitch and Kick log in with their **official logins**. BIG Studio never sees your password.

---

## Reporting bugs

BIG Studio saves a report **by itself** when it:
- hits an error,
- freezes,
- crashes or closes unexpectedly (you'll see a message next time you open it),
- has a stream or recording failure.

For anything else, go to **Diagnostics → Save bug report** and type what happened.

Reports are saved in `%APPDATA%\Streamer\crash-reports` (**Diagnostics → Open reports**).
Send me the `.txt` files, plus a screenshot or short video if you can. Reports never contain
your stream keys, passwords, logins or chat, and your Windows user name is hidden.

---

## Good to know

- **Windows 10 (version 2004 or later) and Windows 11**, 64-bit.
- **Kick**: chat and alerts work with just your channel name. Changing the title or category,
  or sending chat, needs your own free Kick developer app. Settings → Plugins → Kick explains how.
- **YouTube**: streaming works. Built-in YouTube chat and alerts aren't done yet.
- Your settings live in `%APPDATA%\Streamer` and are kept when you update or uninstall.
