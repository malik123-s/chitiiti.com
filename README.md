# 🎲 Chitii - Digital Name Picker & Raffle Draw

> A modern, fair, interactive digital name picker and raffle draw web application with animated shuffling, sound effects, celebration confetti, and winner history.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## ✨ Features

- 🎯 **Fair & Transparent Randomizer**: Truly random selection algorithm with cryptographic fairness.
- 🎰 **Animated Shuffle**: Dynamic slowdown countdown visual effect before revealing the winner.
- 🔊 **Built-in Sound Effects**: Web Audio API audio synthesis for realistic tick countdowns and celebratory fanfare (No external MP3 files needed).
- 🎆 **Particle Celebration Confetti**: Lightweight pure HTML5 canvas confetti explosion on every draw.
- ⚡ **Presets & Quick Actions**: Instant load options for Teams, Raffles, Numbers, and Quick Clear.
- ❌ **Auto-Remove Winner Option**: Toggle to automatically remove drawn winners for multi-round draws.
- 🏆 **Winner History Log**: Keeps track of all previous winners drawn during the session.
- 📱 **Fully Responsive & Dark Mode**: Sleek glassmorphism UI styled for desktop, tablet, and mobile browsers.

---

## 🚀 Live Demo / GitHub Pages

Once published, your app will be accessible at:
`https://<your-github-username>.github.io/<repository-name>/`

---

## 🛠️ How to Publish to GitHub Pages

### Option A: Via GitHub Web Interface (Easiest - No Git CLI required)

1. Go to [GitHub.com](https://github.com) and log in to your account.
2. Click the **`+`** icon in the top right corner and select **New repository**.
3. Name your repository `chitii-name-picker` (or any name you prefer).
4. Set visibility to **Public** and click **Create repository**.
5. On the new repository page, click **"uploading an existing file"**.
6. Drag and drop `index.html`, `README.md`, `LICENSE`, and `.gitignore` into the uploader.
7. Click **Commit changes**.
8. Go to **Settings** > **Pages** (under Code and automation in the left sidebar).
9. Under **Build and deployment** -> **Branch**, select `main` (or `master`) and folder `/ (root)`.
10. Click **Save**. Within 1–2 minutes, your website live link will be ready!

---

### Option B: Via Git Command Line

Open terminal / command prompt in this project directory:

```bash
# 1. Initialize git repository
git init

# 2. Stage all files
git add .

# 3. Create initial commit
git commit -m "Initial commit: Chitii Digital Name Picker"

# 4. Rename branch to main
git branch -M main

# 5. Add your remote GitHub repository (replace with your repo URL)
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git

# 6. Push to GitHub
git push -u origin main
```

Then turn on GitHub Pages in repository **Settings -> Pages** -> choose `main` branch -> Save!

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
