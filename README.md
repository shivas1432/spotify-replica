# Spotify Clone - React Native & Expo

A modern, feature-rich Spotify UI clone built with Expo and React Native. This project showcases advanced mobile app development skills with pixel-perfect design and smooth animations.

## 🚀 Live Demo
[![Expo Demo](https://img.shields.io/badge/Expo-Demo-blue)](https://expo.dev/@shivas1432/spotify-clone)
[![Web Demo](https://img.shields.io/badge/Web-Demo-green)](https://your-spotify-clone.vercel.app)
[![GitHub Stars](https://img.shields.io/github/stars/shivas1432/spotify-clone?style=social)](https://github.com/shivas1432/spotify-clone)

<p align="center">
  <img src="screenshots/screenshare-4.jpg?raw=true" alt="Spotify Clone Demo" />
</p>

## ✨ Features

- **Pixel-Perfect UI:** Authentic Spotify design with attention to detail
- **Cross-Platform:** iOS, Android, and PWA (Web App) support
- **Modern Navigation:** React Navigation v6 with smooth transitions
- **Music Player Controls:** Full-featured audio player interface
- **Search Functionality:** Advanced search with real-time results
- **Album & Playlist Views:** Complete music library experience
- **Smooth Animations:** 60fps animations and micro-interactions
- **Responsive Design:** Optimized for all device sizes
- **Dark Theme:** Spotify's signature dark interface
- **Context API:** Efficient state management

## 🛠️ Technologies Used

- **Framework:** Expo SDK 48
- **Frontend:** React Native 0.71.6
- **Navigation:** React Navigation v6
- **State Management:** React Context & Hooks
- **Icons:** Expo Vector Icons
- **Animations:** React Native Reanimated
- **Gestures:** React Native Gesture Handler
- **Web Support:** React Native Web
- **Development:** Expo CLI, ESLint, Prettier

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- Expo CLI
- iOS Simulator (Mac) or Android Studio
- Expo Go app (for physical device testing)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shivas1432/spotify-clone.git
   cd spotify-clone
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Install web support (if needed):**
   ```bash
   npx expo install @expo/webpack-config
   ```

4. **Start the development server:**
   ```bash
   npm start
   # or
   npx expo start
   ```

5. **Run on specific platforms:**
   ```bash
   # For iOS simulator
   npm run ios
   
   # For Android emulator  
   npm run android
   
   # For web browser
   npm run web
   
   # Or use interactive commands:
   # Press 'a' - open Android
   # Press 'i' - open iOS  
   # Press 'w' - open web
   # Press 'r' - reload app
   ```

## 📱 Testing

### Physical Device
1. Install **Expo Go** app from App Store/Play Store
2. Scan QR code from terminal
3. App will load on your device

### Simulator/Emulator
1. Open iOS Simulator or Android Studio
2. Press `i` for iOS or `a` for Android in terminal
3. App will launch in simulator

## 🤝 Contributing

I welcome contributions to make this Spotify clone even better!

### How to Contribute

1. **Fork the repository**
2. **Create feature branch:** `git checkout -b feature/amazing-feature`
3. **Make your changes and test thoroughly**
4. **Commit changes:** `git commit -m "feat: add amazing feature"`
5. **Push to branch:** `git push origin feature/amazing-feature`
6. **Submit a Pull Request**

### What Can You Contribute?

- 🐛 **Bug Fixes:** Report and fix issues
- ✨ **New Features:**
  - Offline music support
  - Social features (follow artists, share playlists)
  - Audio equalizer
  - Lyrics display
  - Voice commands
  - Podcast support
  - Sleep timer
  - Crossfade between songs
- 🎨 **UI/UX Improvements:** Better animations, themes
- 📱 **Platform Features:** iOS/Android specific optimizations
- 🧪 **Testing:** Unit tests, integration tests
- 📚 **Documentation:** Improve guides and comments

### Development Guidelines

- **Code Style:** Follow React Native best practices
- **Commit Messages:** Use conventional commits
- **Testing:** Test on both iOS and Android
- **Performance:** Optimize for smooth 60fps animations
- **Accessibility:** Ensure app is accessible to all users

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory:
```env
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
API_BASE_URL=your_music_api_url
```

### Expo Configuration
The app is configured in `app.json`:
- App name, version, and description
- Platform-specific settings
- Asset and icon configurations
- Build and deployment settings

## 📦 Deployment

### Expo Application Services (EAS)
```bash
# Install EAS CLI
npm install -g @expo/eas-cli

# Configure EAS
eas build:configure

# Build for iOS
eas build --platform ios

# Build for Android
eas build --platform android

# Submit to app stores
eas submit --platform ios
eas submit --platform android
```

### Expo Web
```bash
# Build for web
npx expo export:web

# Deploy to Netlify/Vercel
# Upload web-build/ folder
```

## 🏗️ Project Structure

```
spotify-clone/
├── src/
│   ├── components/
│   │   ├── Player/
│   │   ├── Playlist/
│   │   ├── Search/
│   │   └── ...
│   ├── screens/
│   │   ├── HomeScreen.js
│   │   ├── PlayerScreen.js
│   │   ├── SearchScreen.js
│   │   └── ...
│   ├── navigation/
│   │   └── AppNavigator.js
│   ├── services/
│   │   └── musicService.js
│   ├── utils/
│   │   └── helpers.js
│   └── constants/
│       └── colors.js
├── assets/
│   ├── images/
│   ├── icons/
│   └── audio/
├── app.json
├── package.json
└── README.md
```

## 🎯 Roadmap

- [ ] Spotify Web API integration
- [ ] Offline music download
- [ ] Social features (friends, sharing)
- [ ] Podcast support
- [ ] Audio equalizer
- [ ] Lyrics synchronization
- [ ] Voice commands
- [ ] Apple CarPlay/Android Auto
- [ ] Chromecast support
- [ ] Sleep timer

## 🐛 Known Issues

- Audio playback requires device audio permissions
- iOS simulator doesn't support audio playback
- Some animations may lag on older devices

## 📱 Device Compatibility

- **iOS:** 12.0+
- **Android:** API level 21+ (Android 5.0+)
- **Expo Go:** Latest version recommended

## 🔐 Privacy & Permissions

This app requests the following permissions:
- **Audio Recording:** For voice search (optional)
- **Media Library:** Access to device music (optional)
- **Network:** For streaming and API calls

## 👨‍💻 Author

**Kanugula Shivashanker**
- GitHub: [@shivas1432](https://github.com/shivas1432)
- LinkedIn: [shivashanker-kanugula](https://www.linkedin.com/in/shivashanker-kanugula-51a512252)
- Website: [shivashanker.com](https://www.shivashanker.com)
- Telegram: [@helpme_coder](https://t.me/helpme_coder)
- Instagram: [@ss_web_innovations](https://www.instagram.com/ss_web_innovations)

*Full-Stack Mobile Developer | React Native, Expo, Node.js | Passionate about mobile app development | Music enthusiast | Open to collaboration.*

## 🙏 Acknowledgments

- Spotify for the amazing design inspiration
- Expo team for the incredible development platform
- React Native community for continuous support
- Music artists and creators worldwide

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🌟 Show Your Support

If you found this project helpful, please:
- ⭐ Star the repository
- 🍴 Fork it to contribute
- 📢 Share it with fellow developers
- 🐛 Report any issues you find
- 💡 Suggest new features

## 📞 Support

Having issues? Need help?
- 📧 Email: shivashanker.dev@gmail.com
- 💬 Telegram: [@helpme_coder](https://t.me/helpme_coder)
- 🐛 GitHub Issues: [Report Bug](https://github.com/shivas1432/spotify-clone/issues)

---

**Rock On!** 🎵🚀

*Built with ❤️ by Kanugula Shivashanker*