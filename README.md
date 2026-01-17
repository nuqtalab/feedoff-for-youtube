# FeedOff for YouTube
**Enjoy YouTube without distractions**

FeedOff for YouTube is a lightweight, privacy-first Chrome extension designed to reduce distractions on YouTube. It helps users hide feeds, Shorts, recommendations, autoplay, and other non-essential interface elements so they can focus on the videos they actually want to watch.

Whether you’re studying, working, or simply trying to avoid endless scrolling, FeedOff turns YouTube into a cleaner, calmer, and more intentional viewing space.

---

## ✨ Features

- 🏠 Hide YouTube home feed  
- 🔀 Redirect home page to Subscriptions (optional)  
- 📉 Hide recommended and related videos  
- 🎬 Hide or blur YouTube Shorts  
- 💬 Hide comments and live chat  
- 📊 Clean video pages (sidebar, end screens, cards, buttons)  
- 🧹 Remove playlists, mixes, trending & explore sections  
- 🔕 Disable autoplay and annotations  
- ⚙️ Fully customizable controls  

---

## 🔐 Privacy First

FeedOff for YouTube is built with privacy in mind.

- No data collection  
- No tracking or analytics  
- No remote code  
- Runs 100% locally in your browser  

All user settings are stored locally using Chrome’s storage API.

Read the full Privacy Policy here:  
👉 **PRIVACY.md**

---

## 🧠 Why Use FeedOff?

- Reduce distractions and improve focus  
- Avoid endless scrolling and recommendation loops  
- Create a clean and minimal YouTube interface  
- Stay in control of your viewing habits  

Perfect for students, professionals, developers, and digital minimalists.

---

## 🚀 Installation

### From Chrome Web Store

1. Open the Chrome Web Store  
2. Search for **FeedOff for YouTube**  
3. Click **Add to Chrome**

---

## 🧭 How to Use

1. Open YouTube  
2. Click the FeedOff icon in the toolbar  
3. Toggle the features you want to hide  
4. Reload the page if needed  
5. Enjoy YouTube without distractions  

---

## 🛡️ Permissions Explained

- **storage** – Saves user preferences locally  
- **activeTab** – Used only when the user clicks a button to reload or reapply changes  
- **host permission (youtube.com)** – Required to modify YouTube’s interface  

No permissions are used beyond the extension’s single purpose.

---

## 📦 Project Structure

feedoff-for-youtube/
│
├── manifest.json          # Chrome extension configuration (MV3)
│
├── content.js             # Main logic: hides feeds, Shorts, UI elements
│
├── popup.html             # Extension popup UI
├── popup.js               # Popup logic (toggles, reload button)
├── popup.css              # Popup styling
│
├── icons/                 # Extension icons
│   ├── icon16.png
│   ├── icon32.png
│   ├── icon48.png
│   └── icon128.png
│
├── PRIVACY.md             # Privacy Policy (Chrome Web Store compliant)
├── README.md              # Project documentation
│
└── LICENSE                # MIT License




---

## 🧩 Single Purpose

FeedOff for YouTube has a single, narrow purpose:  
**to reduce distractions on YouTube by hiding non-essential UI elements and recommendations.**

---

## 🧑‍💻 Developer

Developed and maintained by **NuqtaLab**.

---

## 📬 Support & Feedback

For support, feedback, or bug reports, please use the support page:  
👉 https://forms.gle/UkpnJYCuB7Jgy4XC7  
Or open an issue in this GitHub repository.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🌟 Final Note

FeedOff for YouTube is designed to make YouTube work for you — not the algorithm.

If you find this project helpful, feel free to ⭐ star the repository.
