# Dogs-JavaScript-API 🐶
**Author:** Faiza Khan  
**Project:** Dogs-JavaScript-API
Organized and refined with help from chatgpt.

A simple web app that displays an infinite dog slideshow.  
HTML/CSS handle the slideshow layout/effects, and JavaScript fetches images from a public API.

---

## What it does
- Dropdown to select a dog breed
- Automatically cycles through breed images (infinite slideshow)
- Lightweight, vanilla HTML/CSS/JS

---

## Tech Stack
- **HTML** & **CSS** – structure and slideshow styling
- **JavaScript** – fetch + render images, slideshow logic
- **API** – Dog CEO API (listed under Public APIs)

> Public APIs index: https://github.com/public-apis/public-apis  
> Dog CEO (Dog Images) API: https://dog.ceo/dog-api/

---

## Getting Started
1. Clone the repo and open the folder in VS Code.
2. Open `index.html` in your browser  
   - or use the VS Code **Live Server** extension for auto-reload.
3. Select a breed from the dropdown and enjoy the slideshow.

> If nothing renders, make sure you have elements like:
> ```html
> <div id="breed"></div>
> <div id="slideshow"></div>
> ```

---

## How it works 
- On load, the app fetches the full breed list from `https://dog.ceo/api/breeds/list/all`.
- When a breed is selected, it fetches images from `https://dog.ceo/api/breed/{breed}/images`.
- JavaScript updates the DOM and rotates images on a timer to create the slideshow effect.

---

## Credits
- Project inspired by: **Brad Schiff**  
  YouTube video: https://www.youtube.com/watch?v=AVmGmLFcukM
