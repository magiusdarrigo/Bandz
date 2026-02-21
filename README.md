# Bandz

An iOS app for discovering and managing music events and bands. Browse events, search for bands, and manage your profile -- all in one place.

## Features

- **Home** -- Dashboard with an overview of activity
- **Search** -- Find bands and events
- **Events** -- Browse and explore music events
- **Profile** -- Manage your user profile

## Tech Stack

- **Language:** Swift 4
- **UI:** Storyboards (Interface Builder)
- **Backend:** Firebase (Analytics, Core)
- **Package Manager:** CocoaPods
- **Minimum iOS Version:** 11.2

## Getting Started

### Prerequisites

- macOS with [Xcode](https://developer.apple.com/xcode/) installed (9.0+)
- [CocoaPods](https://cocoapods.org/) (`gem install cocoapods`)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/magiusdarrigo/Bandz.git
   cd Bandz
   ```

2. Install dependencies:

   ```bash
   pod install
   ```

3. Add your Firebase configuration:

   - Create a project in the [Firebase Console](https://console.firebase.google.com/)
   - Download `GoogleService-Info.plist` and place it in the `Bandz/` directory

4. Open the workspace in Xcode:

   ```bash
   open Bandz.xcworkspace
   ```

   > **Note:** Always open the `.xcworkspace` file, not `.xcodeproj`, so that CocoaPods dependencies are included.

5. Select a simulator or connected device and press **Cmd + R** to build and run.

## Project Structure

```
Bandz/
├── Bandz/
│   ├── AppDelegate.swift         # App entry point
│   ├── ViewController.swift      # Main view controller & IBDesignable extensions
│   ├── Assets.xcassets/          # Image assets and app icons
│   ├── Base.lproj/               # Storyboards (Main, LaunchScreen, Home, Events)
│   ├── Home.storyboard           # Home tab UI
│   ├── Search.storyboard         # Search tab UI
│   ├── Events.storyboard         # Events tab UI
│   ├── Profile.storyboard        # Profile tab UI
│   └── Info.plist                # App configuration
├── Podfile                       # CocoaPods dependency specification
├── Podfile.lock                  # Locked dependency versions
└── Bandz.xcworkspace/            # Xcode workspace
```

## License

Copyright 2019 Matteo Agius. All rights reserved.
