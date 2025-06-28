# 🎧 Vinyl Music Player

An interactive vinyl-style music player app for Android. Spin the vinyl to seek through your music — clockwise to move forward, anticlockwise to rewind — just like real DJ turntables! Includes scratch sound effects, Bluetooth audio support, and dynamic album art fetched from Spotify.

---

## ✨ Features

- 🌀 **Spinning Vinyl Animation:** Continuously rotates while music plays.
- 🎚️ **Track Seeking with Gestures:** Rotate clockwise to seek forward, anticlockwise to rewind.
- 🔊 **Scratch Sound Effects:** Realistic scratch sounds when moving the vinyl.
- 🖼️ **Album Cover in Center:** Fetches the current song's album art from Spotify and displays it inside the vinyl.
- 📡 **Bluetooth Support:** Works with Bluetooth speakers or car systems.
- 🎨 **Smooth UI:** Built using Jetpack Compose for fluid animations and modern design.

---

## 🚀 Tech Stack

- 🛠️ **Kotlin + Jetpack Compose**
- 🎶 **Spotify Android SDK**
- 🎧 **MediaSession API**
- 🔥 **Coil (for image loading)**
- 📡 **Bluetooth API**

---

## 🔥 Demo

> *Video/GIF here once available.*

---

## 📲 Installation & Setup

### Prerequisites:
- Android Studio Flamingo or higher.
- Android SDK 33 or above.
- Spotify Developer Account for Client ID.

### Steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/VinylMusicPlayer.git
   cd VinylMusicPlayer



Spotify Developer Setup:

Visit: Spotify Developer Dashboard

Create an app.

Get Client ID and Redirect URI.

Add them to your project in MainActivity.kt:

private val clientId = "YOUR_SPOTIFY_CLIENT_ID"
private val redirectUri = "YOUR_REDIRECT_URI"

🏗️ Project Structure
css
Copy
Edit
app/
 ├── src/
 │   ├── main/
 │   │   ├── java/com/yourname/vinylmusicplayer/
 │   │   │   ├── MainActivity.kt
 │   │   ├── res/
 │   │   │   ├── drawable/  → vinyl_disk.png
 │   │   │   ├── raw/       → scratch_left.mp3, scratch_right.mp3
 │   │   │   └── layout/
 └── build.gradle



⚙️ Permissions Required
Bluetooth Access

Internet (for Spotify integration)

Make sure to enable them in AndroidManifest.xml:

xml
Copy
Edit
<uses-permission android:name="android.permission.BLUETOOTH" />
<uses-permission android:name="android.permission.INTERNET" />


❤️ Credits
Designed & Developed by Ninad Sarulkar

Powered by Spotify Android SDK

Inspired by classic vinyl record players and Mini Cooper Infotainment System
