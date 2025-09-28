# FaviTiles

> **FaviTiles — All Your Favorite Websites, Without the Ads**

FaviTiles is a **self-hosted “speed dial” page** inspired by Opera’s Quick Dial — but **ad-free, privacy-friendly, and fully customizable**.  
Just open it in a browser or host it anywhere (GitHub Pages, local server, etc.).

<img width="2467" height="997" alt="image" src="https://github.com/user-attachments/assets/ebaff222-b5b5-467b-bc60-36f65b1e562b" />


---

## ✨ Features

- **Add / Edit / Delete tiles** — each tile can have:
  - **Custom Title** — any label you want to display.
  - **Custom Icon Path** — point to any image or favicon URL.
- **Drag & Drop Reorder** — arrange tiles easily.
- **Light & Dark themes** — toggle via a modern switch; light is default and remembered.
- **Resizable tile grid** — change two CSS variables (`--tile-min-w` and `--tile-h`) to instantly resize all tiles.
- **Right-click to reveal actions** — edit/delete buttons only appear on right click (prevents accidental clicks).
- **Local storage** — all your tiles live in your browser; no server or database needed.
- **Import / Export** — backup or move tiles between browsers/devices using a JSON file.
- **Mobile friendly** — responsive grid adapts to screen width.
- **Self-hostable** — works from any static host (GitHub Pages, your own server, etc.).

---

## 🚀 Quick Start

### Option 1 — Use the default deployment
You don’t need to deploy anything yourself:  
👉 **[https://favitiles.github.io](https://favitiles.github.io)**  

Just bookmark that URL and use it as your start page.  
All your tiles are stored **locally in your own browser** (localStorage), so your data stays private and never leaves your device.

### Option 2 — Host on GitHub Pages yourself
1. Create a repo (or user/organization site).  
   - For a root site: name the repo **`USERNAME.github.io`**.  
   - For an org site: **`ORGNAME.github.io`**.  
2. Put `index.html` in the repo root and commit.  
3. In **Settings → Pages**, set Source = `main` / `(root)`.  
4. Visit `https://USERNAME.github.io/`.

### Option 3 — Host locally
- Drop the file anywhere and open in your browser.  
- Or run a simple server:  
  ```bash
  python3 -m http.server
  ```
  then go to `http://localhost:8000`.

---

## 🧩 Browser Tips

- **Edge/Chrome:** to make this your **new tab page**, install an extension such as [Custom New Tab URL](https://microsoftedge.microsoft.com/addons/detail/custom-new-tab-url/mkknclhjgdbnakemhfklpbojchhlgnkk).  
  (Edge blocks Group Policy new-tab overrides unless the device is enterprise-managed.)
- Set it as your **home/startup page** directly in browser settings.

---

## 📄 License

MIT — 
This software is provided *“AS IS”*, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.  
Just keep it ad-free ❤️
