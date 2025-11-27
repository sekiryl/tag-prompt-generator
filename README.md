<p align="center">
  <img src="assets/images/logo.png" width="100" alt="Tag Prompt Generator Logo">
</p>

<h1 align="center">Tag Prompt Generator</h1>

<p align="center">
  A sleek, lightweight tag-based prompt generator.<br>
  Built for artists and AI prompt engineers.<br>
  <a href="https://prompt-gen.sekiryl.is-a.dev/"><strong>🔗 Live Demo</strong></a>
</p>

---

## ✨ Features
   🏷️ **Custom Tag Loading** - Load and use your own tag files easily.
   
   🎨 **Theming Support** - Switch between default themes or add your own.
   
   🔍 **Autocomplete Suggestions** - Get tag suggestions as you type.
   
   🧩 **Interactive Tag System** - Drag or use keyboard shortcuts to rearrange tags.
   
   💾 **Prompt Saving** - Save and manage your favorite tag combinations.
   
   📱 **Mobile Friendly** - Fully responsive design, looks great on every screen.

---

## 🛠️ Getting Started

Just clone the repo and serve it with a local HTTP server:

```bash
git clone https://github.com/chimera6174/tag-prompt-gen.git
cd tag-prompt-gen

# Option 1: Python (most systems)
python -m http.server 8000
# or python3 -m http.server 8000

# Option 2: Node.js (if you have it)
npx serve .

# Option 3: PHP (if you have it)
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

**Note:** A local HTTP server is required to load tag files due to browser CORS policies. Simply opening `index.html` directly may cause loading errors.

---

## 📄 License

Licensed under the [GNU GPL v3](LICENSE).
You are free to copy, modify, and redistribute as long as you keep it open-source.

---

## 👤 Credits

- Inspired by various tag-based prompt tools and image generators.
- Built with vanilla HTML, CSS, and JavaScript by [sekiryl](https://github.com/sekiryl).
- [Sortable.js](https://github.com/sortablejs/sortable) for tag sorting.
