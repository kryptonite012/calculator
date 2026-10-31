# Calculator Pro

Calculator Pro is a modern, feature-rich web-based calculator designed to provide both basic and advanced mathematical operations within an intuitive and visually appealing interface. Built using HTML, CSS, and JavaScript, this application focuses on delivering a smooth user experience with responsive design, dynamic interactions, and persistent data storage.

The calculator supports standard arithmetic operations such as addition, subtraction, multiplication, and division, along with advanced functionalities including square root, power calculations, percentage operations, and reciprocal values. It also includes memory functions like Memory Add (M+), Memory Subtract (M−), Memory Recall (MR), and Memory Clear (MC), enabling users to store and reuse values efficiently during complex calculations.

A key highlight of the application is its interactive UI and animations, which enhance usability and engagement. Button clicks include visual feedback effects, while error handling—such as division by zero—triggers smooth animations to alert users without disrupting the experience. The calculator also features a calculation history panel, allowing users to view recent operations and reuse previous results instantly.

The application incorporates a dark mode toggle, providing users with the flexibility to switch between light and dark themes based on their preference. This theme setting, along with calculation history and memory values, is stored using browser LocalStorage, ensuring data persistence across sessions.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `0`–`9`, `.` | Enter numbers |
| `+ - * /` | Operators |
| `Enter` or `=` | Calculate |
| `Backspace` | Delete last digit |
| `Esc` / `Delete` | Clear |
| `%` | Percent |

## Run locally

Open `index.html` in any modern browser. No install or build step is needed. To serve it over HTTP instead:

```bash
python3 -m http.server 8000
```

## Deploy

This repository includes a GitHub Pages workflow (`.github/workflows/pages.yml`).

1. Go to **Settings → Pages** and set **Source** to **GitHub Actions**.
2. Push to the default branch. The site is published at `https://<username>.github.io/calculator/`.

Any static host (Netlify, Vercel, Cloudflare Pages) also works: publish the repository root with no build command.
