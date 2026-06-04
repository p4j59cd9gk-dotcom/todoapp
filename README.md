# To-Do List PWA

A full-featured Progressive Web App (PWA) to-do list — installable on Android and iOS directly from the browser.

## Features
- ✅ Tasks with categories, subtasks, due dates, flags, repeat
- 📅 Calendar view with task markers
- 📊 Stats (streak, completion chart)
- 🎨 Theme color picker
- ⚙️ Full Settings screen
- 🌍 Spanish / English (switch in Settings → Language)
- 💾 Works offline, data saved in browser storage
- 📱 Installable on Android via Chrome → "Add to Home Screen"

---

## Deploy to GitHub Pages (free hosting)

### Step 1 — Create a GitHub repo
1. Go to https://github.com and sign in (or create a free account)
2. Click **New repository**
3. Name it `todo-app` (or anything you like)
4. Make it **Public**
5. Click **Create repository**

### Step 2 — Upload the files
Upload these 3 files to the repo:
- `index.html`
- `manifest.json`
- `sw.js`

You can do this via the GitHub website (drag & drop) or with git:
```bash
git clone https://github.com/YOUR_USERNAME/todo-app.git
cd todo-app
# copy the 3 files here
git add .
git commit -m "Initial PWA"
git push
```

### Step 3 — Enable GitHub Pages
1. In your repo, go to **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Choose branch: **main**, folder: **/ (root)**
4. Click **Save**

Your app will be live at:
`https://YOUR_USERNAME.github.io/todo-app/`

(Takes ~1 minute to deploy)

---

## Install on Android
1. Open Chrome on your Android phone
2. Go to `https://YOUR_USERNAME.github.io/todo-app/`
3. Tap the **⋮ menu** → **Add to Home Screen**
4. Tap **Add**

The app icon appears on your home screen and opens fullscreen, just like a native app.

## Install on iPhone (iOS Safari)
1. Open Safari on your iPhone
2. Go to your GitHub Pages URL
3. Tap the **Share** button (square with arrow)
4. Tap **Add to Home Screen**
5. Tap **Add**

---

## Local testing
Just open `index.html` in Chrome. No server needed for basic use.

For full PWA/offline testing:
```bash
# Install a simple server
npm install -g serve
serve .
# Then open http://localhost:3000
```
