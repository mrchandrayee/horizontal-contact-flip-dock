# Horizontal Contact Flip Dock

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/horizontal-contact-flip-dock/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

This project recreates the **Horizontal Contact Flip Dock** shown in the supplied 18-second screen recording.

## What the video shows

- A dark, almost black page with the heading `Horizontal Contact Flip Dock`
- A centered horizontal dock with seven rounded tiles spelling `CONTACT`
- Each tile flips on hover to show a social/contact icon
- A tooltip appears below the hovered tile
- Visible platform labels include Instagram, YouTube, WhatsApp, LinkedIn, Facebook, Email and Twitter
- A white caption reads `Comment "Flip" for code`
- The source editor shows a `.contact-dock` CSS rule

## CSS transcribed from the visible editor

The visible portion of the `.contact-dock` rule reads:

```css
/* CONTACT DOCK */
.contact-dock {
  display: flex;
  align-items: center;
  gap: 6px;

  padding: 14px 18px;

  background: rgba(255,255,255,.06);
  border: 1px solid rgba(255,255,255,.15);

  border-radius: 20px;

  backdrop-filter: blur(18px);

  box-shadow:
    0 20px 50px rgba(0,0,0,.45),
    inset 0 0 20px rgba(255,255,255,.03);
}
```

The editor also shows the beginning of the comment `/* EACH CHARACTER */`. The remaining HTML and CSS source is not fully visible in the recording, so the flip-card and tooltip implementation is reconstructed to match the observed behavior.

## Run

Unzip the project and open `index.html` in a modern browser. No build tools, npm packages, external images, icon libraries or web fonts are required.

## Files

- `index.html` — seven interactive contact/social tiles
- `style.css` — glass dock, 3D flip transition, platform colors, tooltip and responsive layout
- `README.md` — source transcription and notes

## Before publishing

Update the Email link (`mailto:hello@example.com`) to your real email address and replace the social profile URLs with your own accounts.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
