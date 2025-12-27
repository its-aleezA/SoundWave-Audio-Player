# 🎵 SoundWave: A Modern Audio Player

A sleek, modern web-based audio player with playlist management, built using vanilla JavaScript and implementing core computer science data structures. Features a beautiful gradient UI with full playback controls and playlist functionality.

> [!IMPORTANT]
> This audio player uses modern web APIs and may require user interaction to start playback due to browser autoplay policies. For best results, use Chrome, Firefox, or Edge.

**Key Features**:
- ✅ **Doubly Linked List** for efficient playlist management
- ✅ **Static Queue** for playback history tracking
- ✅ **Beautiful Gradient UI** with glassmorphism effects
- ✅ **Full Playback Controls** (play, pause, next, previous, shuffle, repeat)
- ✅ **Playlist Management** (create, view, delete songs)
- ✅ **Responsive Design** works on desktop and mobile
- ✅ **Keyboard Shortcuts** for quick control

---

## 📖 Overview

This project implements a fully-featured audio player in a single HTML file using modern web technologies. The player demonstrates practical application of data structures like Doubly Linked Lists for playlist management and Static Queues for tracking playback history. The interface features a dark theme with gradient accents and smooth animations.

---

## 📱 Live Demo

Check out the live demo [here](https://its-aleeza.github.io/SoundWave-Audio-Player/)

---

## 🚀 Quick Start

### 1. Prerequisites
No installation required! Simply open the HTML file in a modern web browser.

### 2. Basic Usage
```html
<!-- Open the HTML file in your browser -->
<!-- Click "Select Audio Files" to load your music -->
<!-- Use playback controls to manage your music -->
```

### 3. Loading Audio Files
1. Click "Select Audio Files" button
2. Choose multiple audio files from your computer
3. Files will appear in your library
4. Click any song to start playing

### 4. Creating Playlists
1. Load audio files first
2. Click "Create Playlist" button
3. Enter playlist name
4. Select songs by clicking on them
5. Click "Create Playlist" to save

---

## 🎹 Controls

### Player Controls
- **▶/⏸** Play/Pause (Spacebar)
- **⏮** Previous Track (Left Arrow)
- **⏭** Next Track (Right Arrow)
- **🔀** Toggle Shuffle
- **🔁** Toggle Repeat

### Navigation
- **📚 Library**: View all loaded songs
- **🕐 History**: View recently played tracks
- **Playlists**: Access your created playlists

---

## 🏗️ Architecture

### Data Structures Implemented

#### Doubly Linked List
- Used for playlist song management
- Enables efficient insertion and deletion
- Supports traversal in both directions

#### Static Queue
- Fixed-size queue for playback history
- Automatically removes oldest entries when full
- Capacity: 5 most recent tracks

### Core Classes

- **`Node`**: Basic linked list node
- **`DoublyLinkedList`**: Complete doubly linked list implementation
- **`StaticQueue`**: Fixed-capacity queue
- **`Track`**: Audio track representation
- **`Playlist`**: Playlist management with history
- **`AudioPlayer`**: Main application controller

---

## 🎨 UI Features

- **Glassmorphism Design**: Frosted glass effects with backdrop blur
- **Gradient Accents**: Purple-blue gradient theme
- **Smooth Animations**: CSS transitions and transforms
- **Responsive Layout**: Adapts to mobile and desktop
- **Interactive Elements**: Hover effects and visual feedback

---

## 📁 Supported Audio Formats

- MP3
- WAV
- OGG
- FLAC
- M4A
- AAC

---

## ⌨️ Keyboard Shortcuts

- **Spacebar**: Play/Pause
- **Left Arrow**: Previous Track
- **Right Arrow**: Next Track

---

## 🛠️ Technical Details

### Languages Used
Built with
- Vanilla JavaScript
- HTML5
- CSS3
  
### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

### Storage
- All data stored in memory (no persistent storage)
- Playlists and history reset on page refresh

### Performance
- Efficient O(1) operations for queue operations
- O(n) traversal for linked lists
- Blob URLs for efficient audio file handling

---

## 🔧 Customization

The player can be easily customized by modifying:
- Color schemes in CSS variables
- Queue capacity in `StaticQueue` constructor
- UI layout in CSS grid definitions
- Supported audio formats in file filter

---

## 👤 Author

[Aleeza Rizwan](https://github.com/its-aleezA)

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

> [!NOTE]
> This audio player runs entirely in your browser - no audio files are uploaded to any server. All processing happens locally on your device.
