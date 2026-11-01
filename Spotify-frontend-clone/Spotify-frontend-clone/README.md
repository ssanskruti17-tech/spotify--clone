# 🎧 Spotify Frontend Clone

A modern Spotify-inspired music streaming interface built with **only HTML5 and CSS3** (no JavaScript, no frameworks).

> **Note:** This is a visual UI project. Search, filters, and the music player are design only - nothing plays.

## ✨ Features
- 5 pages: Home, Search, Your Library, Playlist, Artist
- Sidebar that collapses to an icon rail on tablets and a bottom tab bar on phones
- Card hover animations with a green play button that slides up
- Fixed bottom music player (cover, controls, progress bar, volume, queue, devices)
- Song table with hover play icons, like and more-options buttons
- CSS Grid + Flexbox layouts, CSS variables, custom scrollbars, reduced-motion support

## 📂 Project Structure
```text
Spotify-frontend-clone/
├── index.html  search.html  library.html  playlist.html  artist.html
├── css/
│   ├── base.css        variables, reset, scrollbars, gradients
│   ├── layout.css      sidebar, main panel, top bar, sections
│   ├── components.css  cards, chips, song table, banners
│   ├── player.css      bottom player + mobile tab bar
│   └── responsive.css  tablet and mobile rules (loaded last)
└── assets/
    ├── images/   logo + photographic cover art (art/ = covers, artists, banner)
    └── icons/    original PNG icons
```

## 🚀 Run Locally
1. Open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` → **Open with Live Server**.

Needs an internet connection for Font Awesome icons and the Montserrat font (CDN).

## 🛠️ Tech
HTML5 · CSS3 · Font Awesome · Google Fonts (Montserrat)

## Image credits
The refreshed cover and banner photographs are sourced from [Unsplash](https://unsplash.com/).
