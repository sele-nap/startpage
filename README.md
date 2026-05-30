# ✦ startpage

> Aesthetic new tab page — because the default one is a crime.

A minimal, self-contained browser startpage built with a single HTML file. No dependencies, no build step, no nonsense.

![Rosé Pine theme](https://img.shields.io/badge/theme-Rosé%20Pine-c4a7e7?style=flat-square)
![Vanilla HTML](https://img.shields.io/badge/built%20with-HTML-eb6f92?style=flat-square)

## Features

- **Live clock** — updates every second, displays the full date in lowercase italic
- **Weather** — current temperature & conditions via [Open-Meteo](https://open-meteo.com/) (no API key needed)
- **Quick links** — GitHub, Google Calendar, Gmail, Notion
- **Cat fact of the day** — daily feline wisdom courtesy of [catfact.ninja](https://catfact.ninja/)
- **Rosé Pine** color scheme, elegant serif fonts (Cormorant Garamond & Crimson Pro)

## Usage

Just open `startpage.html` in your browser and set it as your new tab page.

On Windows, copy `startpage.bat.example` to `startpage.bat`, replace `YOUR_USERNAME` with your actual username, and run it — it opens the startpage directly in Chrome.

## Customization

Edit the links section in `startpage.html` to add your own bookmarks. Each card follows this structure:

```html
<a class="link-card love" href="https://your-url.com" target="_blank">
  <span class="icon">⬡</span>
  <span class="label">Label</span>
  <span class="sublabel">sublabel</span>
</a>
```

Color accents available: `love` (pink), `gold`, `rose`, `iris` (purple), `foam` (teal).

To change the weather location, update the `latitude` and `longitude` values in the `fetchWeather()` function.
