<div align="center">

# 🌟 Quotify

### *Daily inspiration at your fingertips*

A beautiful React Native app with 2,127+ inspiring quotes, smart category filtering, home screen widgets, and elegant design. Works completely offline with instant quote loading.

[![React Native](https://img.shields.io/badge/React%20Native-0.80.0-blue.svg)](https://reactnative.dev/)
[![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-lightgrey.svg)](https://github.com/facebook/react-native)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

[Features](#-features) • [Screenshots](#-screenshots) • [Installation](#-installation) • [Usage](#-usage) • [Widgets](#-widgets)

</div>

---

## ✨ Features

### 🎯 **Core Features**
- **Random Quote Generation** - Instant access to 2,127+ inspiring quotes
- **Smart Category Filtering** - Find quotes by topic - Motivation, Success, Wisdom, and 20+ more categories
- **Fully Offline** - No internet connection required, works anywhere
- **Favorites System** - Save and manage your favorite quotes
- **Beautiful UI** - Stunning gradient backgrounds and modern design
- **Cross-Platform** - Available for both iOS and Android

### 📱 **Home Screen Widgets**
- **iOS Widgets** - WidgetKit-based home screen widgets
- **Android Widgets** - Native home screen widgets
- **Auto-Updates** - Widgets refresh every 30 minutes
- **Manual Refresh** - Tap to refresh widget content
- **Seamless Sync** - Widgets update when you fetch new quotes in the app

### 🚀 **Smart Features**
- **Categories & Filters** - Filter quotes by tags like Motivation, Success, Wisdom, and more
- **Local Quote Database** - 2,127+ curated quotes stored locally for instant access
- **Lightning Fast** - No loading times or network dependencies
- **Share Functionality** - Share quotes with friends
- **Copy to Clipboard** - Quick copy for easy sharing
- **Elegant Animations** - Smooth transitions and loading states

---

## 📸 Screenshots

### Main App Experience
<div align="center">
  <table>
    <tr>
      
      <td align="center"><strong>Android</strong></td>
    </tr>
    <tr>
      
      <td><img src="screenshots/homescreen-android.png" width="250" alt="Android Home Screen"></td>
    </tr>
    <tr>
      <td><em>Beautiful gradient UI with inspiring quotes</em></td>
      <td><em>Cross-platform consistency</em></td>
    </tr>
  </table>
</div>

### Favorites & Sharing
<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Favorites Management</strong></td>
      <td align="center"><strong>Adding to Favorites</strong></td>
    </tr>
    <tr>
      <td><img src="screenshots/favourites-screen-ios.png" width="250" alt="iOS Favorites Screen"></td>
      <td><img src="screenshots/favourite-quote-ios.png" width="250" alt="iOS Add to Favorites"></td>
    </tr>
    <tr>
      <td><img src="screenshots/favourites-screen-android.png" width="250" alt="Android Favorites Screen"></td>
      <td><img src="screenshots/favourite-quote-android.png" width="250" alt="Android Add to Favorites"></td>
    </tr>
    <tr>
      <td><em>Manage your saved quotes</em></td>
      <td><em>Heart to save inspirational quotes</em></td>
    </tr>
  </table>
</div>

### Share Functionality
<div align="center">
  <table>
    <tr>
      <td align="center"><strong>iOS Share</strong></td>
      <td align="center"><strong>Android Share</strong></td>
    </tr>
    <tr>
      <td><img src="screenshots/share-quote-ios.png" width="250" alt="iOS Share Quote"></td>
      <td><img src="screenshots/share-quote-android.png" width="250" alt="Android Share Quote"></td>
    </tr>
    <tr>
      <td><em>Native iOS sharing experience</em></td>
      <td><em>Android system share integration</em></td>
    </tr>
  </table>
</div>

### Home Screen Widgets
<div align="center">
  <table>
    <tr>
      <td align="center"><strong>iOS Widget</strong></td>
      <td align="center"><strong>Android Widget</strong></td>
    </tr>
    <tr>
      <td><img src="screenshots/widget-ios.png" width="300" alt="iOS Home Screen Widget"></td>
      <td><img src="screenshots/widget-android.png" width="300" alt="Android Home Screen Widget"></td>
    </tr>
    <tr>
      <td><em>WidgetKit integration with auto-updates</em></td>
      <td><em>Native Android widget with refresh button</em></td>
    </tr>
  </table>
</div>

---

## 🛠 Installation

### Prerequisites

- **Node.js** 18+ 
- **React Native CLI** 
- **Android Studio** (for Android development)
- **Xcode** 12+ (for iOS development)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/quotify.git
   cd quotify
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **iOS Setup**
   ```bash
   cd ios
   bundle install
   bundle exec pod install
   cd ..
   ```

4. **Run the app**
   ```bash
   # For iOS
   npm run ios
   
   # For Android
   npm run android
   ```

---

## 🎮 Usage

### Getting Started
1. **Launch the app** to see your first inspiring quote
2. **Tap "New Quote"** to instantly get a fresh quote from our local collection
3. **Tap the heart icon** to save quotes to your favorites
4. **Use the share button** to spread inspiration with friends
5. **Access favorites** via the favorites button in the top corner

### Discover Quotes by Category
1. **Tap the "Filter" button** to open the category selection screen
2. **Browse popular categories** like Motivation, Success, Wisdom, Inspirational, and more
3. **Select one or multiple categories** to filter quotes by your interests
4. **Apply filters** to get quotes that match your current mood or needs
5. **View category tags** displayed below each quote to see what topics it covers
6. **Clear filters** anytime to return to seeing all quotes

### Always Available
- Quotify works completely offline with 2,127+ curated quotes stored locally
- No internet connection required - perfect for travel or low connectivity areas
- Instant quote loading with no network delays
- All features including favorites and category filtering work without any internet connection
- Smart filtering happens locally for lightning-fast category browsing

---

## 📲 Widgets

### Android Widgets
1. **Long press** on your home screen
2. **Select "Widgets"** from the menu
3. **Find and add** the Quotify widget
4. **Enjoy** automatic quote updates every 30 minutes

### iOS Widgets
1. **Long press** on your home screen
2. **Tap the "+" button** in the top corner
3. **Search for "Quotify"** in the widget gallery
4. **Choose your size** (Small or Medium) and add to home screen

### Widget Features
- ✅ Auto-refresh every 30 minutes
- ✅ Manual refresh by tapping
- ✅ Seamless app integration
- ✅ Beautiful gradient design
- ✅ Works completely offline with local quotes

---

## 🏗 Tech Stack

### Core Technologies
- **React Native** 0.80.0 - Cross-platform mobile framework
- **TypeScript** - Type-safe JavaScript
- **React** 19.1.0 - UI library

### Key Libraries
- **AsyncStorage** - Local data persistence and favorites management
- **Vector Icons** - Beautiful iconography
- **Linear Gradient** - Stunning visual effects
- **Clipboard** - Copy functionality
- **Push Notifications** - Future notification features

### Data Source
- **Local Quote Database** - 2,127+ curated quotes stored in JSON format
- **No External Dependencies** - Completely self-contained for maximum reliability

---

## 🔧 Development

### Project Structure
```
quotify/
├── components/           # React Native components
│   ├── QuoteGenerator.jsx    # Main quote display
│   ├── FavoritesScreen.jsx   # Favorites management
│   ├── QuoteCard.jsx         # Quote display card
│   └── GradientBackground.jsx # UI background
├── services/            # Business logic
│   ├── QuoteService.js      # Local quote management
│   └── WidgetService.js     # Widget management
├── quotes.json          # Local database of 2,127+ quotes
├── android/             # Android-specific code
│   └── app/src/main/java/com/quotify/
├── ios/                 # iOS-specific code
│   └── QuotifyWidget/       # iOS widget extension
└── __tests__/           # Test files
```


<div align="center">

### Made with ❤️ and React Native

*Bringing daily inspiration to your mobile device*

[⬆ Back to top](#-quotify)

</div>
