# Google Wallpapers - Pixel & OEM Unlocker

![Android](https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=flat-square&logo=android)
![License](https://img.shields.io/badge/License-GPL-blue.svg?style=flat-square)
![Release](https://img.shields.io/github/v/release/osmanonurkoc/OEM_Wallpaper_Images?style=flat-square)

A modified Android extension APK that natively integrates exclusive Pixel and OEM wallpapers into the stock **Google Wallpapers** app. 

Originally based on the Pixel 2 era `com.google.android.apps.wallpaper.nexus` stub app (which was used by Google to deliver device-exclusive wallpapers), this mod expands the library massively. It acts as a resource injector, adding dozens of new categories and hundreds of high-quality wallpapers directly into your native wallpaper picker without needing a custom gallery app.

## ✨ Features

* **Native Integration:** Wallpapers appear seamlessly inside the official Google Wallpapers app as native categories.
* **Massive Pixel Collection:** Includes the complete set of wallpapers from **Pixel 1 to Pixel 10** series, including the Pixel Fold and A-series devices.
* **OEM Collections:** Contains hand-picked, high-quality wallpapers from various OEMs.
* **No Root Required:** Simply install the APK alongside the official Google Wallpapers app.
* **Categorized Properly:** All wallpapers are neatly organized with their original titles, subtitles, and featured cover images.

## 📦 Included Collections

This mod injects the following categories into your device:
- **Pixel Series:** Pixel 1, Pixel 2, Pixel 3, Pixel 4 & 4a, Pixel 5, Pixel 6, 6a & 6 Pro, Pixel 7 & 7a, Pixel 8, 8a & 8 Pro, Pixel 9 Series, Pixel 10 Series.
- **Foldables:** Pixel Fold & Pixel 9 Pro Fold.
- **Special Collections:** "For Fun", "Keep Looking", Minerals, Plants, and more.
- **OEM Collections:** Nothing Phone 1, 2, 2a, 3, 3a Lite, 3a Pro, 4a, 4a Pro & CMF 1

## 🚀 Installation

1. Make sure you have the official [Google Wallpapers](https://play.google.com/store/apps/details?id=com.google.android.apps.wallpaper) app installed from the Play Store.
2. Go to the [Releases](https://github.com/osmanonurkoc/OEM_Wallpaper_Images/releases/latest) page and download the latest `.apk` file.
3. Install the APK on your Android device (you may need to allow installation from unknown sources).
4. Long-press your home screen, select **Wallpapers & style** (or open the Google Wallpapers app directly).
5. See all of the newly unlocked Pixel and OEM categories at the top!

## 🛠️ How It Works (For Nerds)

The official Google Wallpapers app is designed to look for specific metadata and XML arrays exposed by other packages (specifically `com.google.android.apps.wallpaper.nexus`). 
By decompiling this legacy stub app and updating its `public.xml`, `arrays.xml`, and `strings.xml`, this project feeds new drawable resources and localized strings back to the main app dynamically. 

## ⚠️ Disclaimer

This is a community-made modification. I am not affiliated with Google or any other OEMs. All wallpaper images and artwork belong to their respective creators and copyright holders.

---
*Created by [@osmanonurkoc](https://osmanonurkoc.com/osmanonurkoc)*
