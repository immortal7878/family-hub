# 🏠 Family Hub — Command Center

A lightweight PWA (Progressive Web App) for managing your family's calendar, chores, grocery list, and bulletin board. Works offline and can be installed on your phone's home screen like a native app.

## 👨‍👩‍👧‍👦 Family Members
- **Serge** (Dad) 👨
- **Yulya** (Mom) 👩
- **Alice** (Daughter) 👧
- **Matthew** (Son) 👦

## ✨ Features
- 📅 **Calendar** — Monthly view with color-coded events per family member
- ✅ **Chores** — Task assignments with progress tracking and recurring schedules
- 🛒 **Groceries** — Shopping list organized by category
- 📌 **Bulletin Board** — Sticky-note style family message board with pinning

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1: Create a GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `family-hub` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2: Upload Files
1. Click **"uploading an existing file"** on the new repo page
2. Drag and drop ALL 5 files from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to your repo **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Set branch to `main` and folder to `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes, then your app is live at:
   ```
   https://YOUR-USERNAME.github.io/family-hub/
   ```

## 📱 Install on Your Phone

### iPhone (Safari)
1. Open the URL in **Safari**
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — done!

### Android (Chrome)
1. Open the URL in **Chrome**
2. Tap the **three dots** menu (top right)
3. Tap **"Add to Home Screen"** or **"Install App"**
4. Tap **Install** — done!

## 💾 Data Storage
All data is saved in your browser's localStorage, so it persists between visits. Each device maintains its own data. Clearing browser data will reset the app.

## 🔧 Customization
Edit `index.html` to change family member names, colors, or default data. Everything is in a single file for simplicity.
