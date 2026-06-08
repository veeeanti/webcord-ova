# Webcord Android

A Discord client with a retro terminal aesthetic, built with Cordova for Android.

## Features

- Terminal-style green-on-black interface
- Boot animation sequence
- Direct messages and server browsing
- Channel list with message viewing
- Bot token and user token support

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Cordova CLI](https://cordova.apache.org/) (`npm install -g cordova`)
- Android SDK (for building the APK)

## Setup

### Cordova Build

```bash
npm run add-android    # Add Android platform
npm run build          # Build APK
npm run emulate        # Run on emulator
```

## Project Structure

```
.
├── config.xml          # Cordova configuration
├── package.json
└── www/
    └── index.html      # Frontend application
```

## License

Apache-2.0
