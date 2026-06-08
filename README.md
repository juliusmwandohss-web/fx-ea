# 🌍 East Africa Currency Converter

A live business currency converter covering 9 East African currencies:
**KES · UGX · TZS · RWF · BIF · ETB · CDF · SOS · SSP**

Features: Live rates · Bulk conversion · History log · Print/export · Works as phone app

---

## 🚀 Deploy to Vercel (Free, 5 minutes)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Upload this project to GitHub
1. Click **"New repository"** on GitHub
2. Name it `ea-currency-converter`
3. Click **"uploading an existing file"**
4. Upload ALL files from this folder (keep the folder structure)
5. Click **"Commit changes"**

### Step 3 — Deploy on Vercel
1. Go to https://vercel.com and sign up with your GitHub account
2. Click **"Add New Project"**
3. Select your `ea-currency-converter` repository
4. Click **"Deploy"** — Vercel auto-detects React
5. In ~2 minutes you'll get a live link like:
   `https://ea-currency-converter.vercel.app`

---

## 📱 Install on Your Phone (Android & iPhone)

Once deployed on Vercel:

**Android (Chrome):**
1. Open the Vercel link in Chrome
2. Tap the 3-dot menu (⋮)
3. Tap **"Add to Home screen"**
4. It installs with the EA FX icon — works like a real app!

**iPhone (Safari):**
1. Open the Vercel link in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Done!

---

## 🏪 Publish on Google Play Store

Once your app is live on Vercel:

1. Go to https://www.pwabuilder.com
2. Enter your Vercel app URL
3. Click **"Package for stores"** → choose **Google Play**
4. Download the `.aab` file
5. Create a Google Play Developer account at https://play.google.com/console ($25 one-time fee)
6. Upload the `.aab` file and fill in your app details
7. Submit for review (usually approved in 1–3 days)

---

## 💻 Run Locally (for developers)

```bash
npm install
npm start
```
Opens at http://localhost:3000

```bash
npm run build
```
Creates a production build in the `/build` folder.

---

## 📁 Project Structure

```
ea-converter/
├── public/
│   ├── index.html       # HTML shell with PWA meta tags
│   ├── manifest.json    # PWA manifest (makes it installable)
│   ├── icon-192.png     # App icon (small)
│   ├── icon-512.png     # App icon (large)
│   └── favicon.ico      # Browser tab icon
├── src/
│   ├── index.js         # React entry point
│   └── App.jsx          # Main app (all logic + UI)
├── package.json         # Dependencies
└── README.md            # This file
```

---

Built with React · Powered by Claude AI for live rates
