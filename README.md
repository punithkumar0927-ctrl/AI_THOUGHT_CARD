# 🤖 AI Thought Card

An interactive 3D greeting card built with pure HTML, CSS and a little JavaScript. A glowing AI-brain cover opens like a real card, then turns page by page to reveal two thoughts.

## ✨ How it works

1. **Click the cover** to open the card and see **Thought 1**:
   *"Life is an AI model; every experience is data, every mistake is training, and every dream is the prediction."*
2. **Click again** to turn the page and see **Thought 2**:
   *"Life is my algorithm; I learn from every error, adapt to every change, and keep optimizing my dreams."*
3. **Click once more** to close the card. Click the turned left page (or press ← ) to go back a page.

Keyboard: `Enter` / `Space` / `→` next, `←` previous.

## 📁 Project Structure

```
ai-thought-card/
├── index.html   # Card markup and page-turn script
├── styles.css   # 3D flip animation and styling
├── cover.jpg    # Front cover artwork
├── page1.jpg    # Thought 1
└── page2.jpg    # Thought 2
```

## 🚀 Getting Started

```bash
git clone https://github.com/punithkumar0927-ctrl/Greeting_card
```

Open `index.html` in any modern browser. An internet connection is only needed for the Google Font used by the hint text.

## 🚀 local host
http://localhost:8137/

## 🎨 Customization

- Replace `cover.jpg`, `page1.jpg` and `page2.jpg` with your own artwork (keep the same portrait ratio, about 9:16).
- Adjust the card size with the `--w` variable at the top of `styles.css`.
- Change the hint messages in the `hints` array in `index.html`.

## 🛠️ Built With

HTML5 · CSS3 (3D transforms, transitions) · Vanilla JavaScript

## 📄 License

Free for personal use. Add a license of your choice (for example, MIT) if you plan to share it more widely.
