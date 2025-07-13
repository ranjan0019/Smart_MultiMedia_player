# 🎵 Smart Multimedia Player

Smart Multimedia Player is a Python-based desktop application that allows users to **search and stream audio or video directly from YouTube**. With a clean interface and smart features like voice-style playback control, volume slider, and progress tracking, it's a perfect lightweight alternative to bulky players.

---

## 🚀 Features

- 🔍 Search and play songs or videos using YouTube
- 🎧 Stream both **audio-only** and **full video** content
- ⏸️ Pause, ▶️ Resume, ⏹ Stop controls
- 🔊 Volume control (0–200%)
- ⏱ Playback progress bar
- 💾 Downloads audio to a local folder (`downloaded_songs`)
- 🧠 Multi-threaded for smoother search & play experience
- 🎨 User-friendly interface built with **Tkinter**

---

## 🛠️ Tech Stack

| Component      | Library          |
|----------------|------------------|
| GUI            | `tkinter`, `ttk` |
| Audio playback | `pygame`, `vlc`  |
| Streaming      | `yt-dlp`         |
| Threading      | `threading`      |

---

## 📦 Requirements

- Python 3.7+
- [ffmpeg](https://ffmpeg.org/) installed and added to PATH
- Install the required Python packages:
```bash
pip install pygame yt-dlp python-vlc
