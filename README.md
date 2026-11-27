<p align="center">
  <img src=".github/assets/meetube/icon.png" width="112" alt="MeeTube logo">
</p>

<h1 align="center">MeeTube</h1>

<p align="center">
  <b>YouTube, reimagined. Different by design. Smooth by nature.</b>
</p>

<p align="center">
  <a href="https://github.com/no-coder-pro/meetube/releases/latest"><img src="https://img.shields.io/github/v/release/no-coder-pro/meetube?style=for-the-badge&label=Release&color=ff0033" alt="Release"></a>
  <a href="https://github.com/no-coder-pro/meetube/stargazers"><img src="https://img.shields.io/github/stars/no-coder-pro/meetube?style=for-the-badge&color=gold" alt="Stars"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPLv3-blue?style=for-the-badge" alt="License: GPLv3"></a>
  <a href="https://t.me/meetubecommunity"><img src="https://img.shields.io/badge/Telegram-Community-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://buymeacoffee.com/yashwynth"><img src="https://img.shields.io/badge/Support%20Original%20Creator-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=000000" alt="Support Original Creator"></a>
</p>

---

### 💖 Original Project & Special Credits
> [!NOTE]
> **MeeTube** was originally created and designed with immense passion by **Yash ([@yashoncode](https://github.com/yashoncode))**. 
> All core UI concepts, liquid glass aesthetics, and the MeeTune music experience originate from the upstream [yashoncode/meetube](https://github.com/yashoncode/meetube) repository.
> 
> If you love MeeTube, please consider supporting the original creator:
> - **Original Repository:** [github.com/yashoncode/meetube](https://github.com/yashoncode/meetube)
> - **Support Yash:** [Buy me a coffee](https://buymeacoffee.com/yashwynth) | UPI (`yashwynth@slc`)
> - **Telegram Community:** [t.me/meetubecommunity](https://t.me/meetubecommunity)

---

**A YouTube video and music client, all in one app:** MeeTube for videos, and MeeTune, its music side, one tap away.

No ads. No sponsor interruptions. Just a gorgeous liquid frosted glass interface, synced live lyrics, background playback, high-speed multi-threaded downloads, and position resume.

<p align="center">
  <img src=".github/assets/meetube/showcase.webp" width="100%" alt="MeeTube Showcase: Watch, Synced lyrics, Home autoplay, Channels, YouTube mode, Equalizer, and 4K Downloads">
</p>

---

## 📥 Download MeeTube (Latest Release: v3.6.4)

Get the appropriate APK for your Android device (Android 7.0+):

| Architecture / Device Type | Description | Download Link |
| :--- | :--- | :--- |
| **arm64-v8a** (64-bit) | Recommended for almost all modern Android phones | [⬇️ Download arm64-v8a](https://github.com/no-coder-pro/meetube/releases/download/v3.6.4/mobile-stmobile-arm64-v8a-release.apk) |
| **armeabi-v7a** (32-bit) | For older or budget Android smartphones | [⬇️ Download armeabi-v7a](https://github.com/no-coder-pro/meetube/releases/download/v3.6.4/mobile-stmobile-armeabi-v7a-release.apk) |
| **Universal** (All Devices) | Works on every Android device (larger file size) | [⬇️ Download Universal](https://github.com/no-coder-pro/meetube/releases/download/v3.6.4/mobile-stmobile-universal-release.apk) |
| **x86** (Intel / AMD) | For Android emulators and x86 Android PCs | [⬇️ Download x86](https://github.com/no-coder-pro/meetube/releases/download/v3.6.4/mobile-stmobile-x86-release.apk) |

👉 **Full Release Notes & Changelogs:** [Browse All Releases](https://github.com/no-coder-pro/meetube/releases)

---

## ✨ Key Features & Enhancements

### 🚀 Custom Enhancements in this Build
- **⚡ Supercharged Multi-threaded Downloads:** Boosted parallel worker threads (up to 4–8 parallel streams) and increased I/O buffers to 128 KB, bypassing YouTube CDN throttling for maximum speeds (5–10+ MB/s).
- **⏱️ Download Playback Position Resume:** Downloaded video and audio files accurately remember and resume right where you left off, with visual progress indicators on library cards.
- **🎨 Refined Modern Navigation Bar:** Clean, modern outline style for the Shorts tab matching Home, Subs, and Downloads. Clean light-mode frosted glass headers with no harsh shadow rings.
- **🔋 Optimized Battery & Memory:** Eliminated background Discord polling threads and unneeded mini-games to minimize RAM and CPU overhead.
- **▶️ Home Feed Video Autoplay:** Seamless inline playback with interactive Play/Pause controls directly on video cards.

---

### 🎵 MeeTune — The Built-in Music Experience
Tap the top logo on Home to instantly transform MeeTube into a dedicated music streaming player.
- 🎤 **AI Karaoke (Beta):** Removes vocals from any song on-device with zero server uploads.
- 🎧 **MeeTuneMix (DJ Crossfade):** Seamless transitions between songs without abrupt cuts or volume jumps.
- 📜 **Live Synced Lyrics:** Real-time line-by-line lyrics display.
- 🔊 **Spatial Audio & Equalizer:** MIT KEMAR spatial audio model, cinema bass boost, and customizable EQ presets with volume boost up to 200%.
- 🚗 **Android Auto Support:** Full in-car interface with voice search, recents, and library playlists.

---

### 🛡️ Pure Streaming Experience
- 🚫 **Ad-Free & SponsorBlock:** Automatically blocks YouTube video ads and skips embedded sponsor segments, intros, and reminders.
- 👎 **Return YouTube Dislike:** Restores accurate real-time dislike counts on all videos.
- 🎯 **DeArrow Integration:** Replaces sensationalized clickbait thumbnails and titles with clean, descriptive community ones.
- 📱 **Background & PiP Playback:** Continue listening with your screen turned off or while multitasking in Picture-in-Picture mode.
- 📺 **Android TV Companion:** Prefer watching on the big screen? Check out [MeeTube TV](https://github.com/yashoncode/meetube-tv).

---

## 🛠️ Building from Source

To build MeeTube APKs locally:

```bash
# Clone the repository with submodules
git clone --recurse-submodules https://github.com/no-coder-pro/meetube.git
cd meetube

# Build debug APK for testing
./gradlew :mobile:assembleStmobileDebug

# Build release APKs (outputs to mobile/build/outputs/renamed_apks/)
./gradlew :mobile:assembleStmobileRelease
```

---

## 🤝 Acknowledgments & Credits

MeeTube stands on the shoulders of incredible open-source projects and contributors:

- **[Yash (@yashoncode)](https://github.com/yashoncode)** — The visionary creator of MeeTube and MeeTune.
- **[SmartTube](https://github.com/yuliskov/SmartTube)** by **[@yuliskov](https://github.com/yuliskov)** — The legendary open-source engine powering the core media backend.
- **[NewTube](https://github.com/aleixrodriala/newtube)** by **[@aleixrodriala](https://github.com/aleixrodriala)** — Foundations for the modern Android client.
- **[AutoEq](https://github.com/jaakkopasanen/AutoEq)** by **[@jaakkopasanen](https://github.com/jaakkopasanen)** — Precision headphone EQ profiles.
- **[Return YouTube Dislike](https://returnyoutubedislike.com/)** & **[SponsorBlock](https://sponsor.ajay.app/)** — Keeping videos clean and honest.
- **Upstream Contributors & Translators:** Thanks to all developers and community members who report issues, translate strings, and submit fixes.

---

## 📄 License & Disclaimer

- **License:** MeeTube is licensed under the [GNU General Public License v3.0 (GPLv3)](LICENSE). Modules originating from SmartTube and NewTube retain their respective MIT and upstream licenses. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for full details.
- **Disclaimer:** MeeTube is an independent open-source client and is not affiliated with, endorsed by, or sponsored by YouTube, Google LLC, or Alphabet Inc.
