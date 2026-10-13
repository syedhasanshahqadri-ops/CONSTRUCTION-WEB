# Construction Website

A simple, responsive, single-page construction company website built with **pure HTML and internal CSS**. No JavaScript, no frameworks, no build tools. Just open `index.html` in a browser.

The layout is inspired by the free Colorlib "Construction" template (CC BY 3.0).

---

## Features

- Single file: all CSS is inside the `<style>` tag of `index.html`
- Fully responsive (desktop, tablet, mobile)
- Smooth hover effects on menu, buttons, cards, project images and links
- Sticky header with top contact bar
- Clickable phone (`tel:`) and email (`mailto:`) links
- Images loaded from URLs, so no image files to download
- Easy colour control through CSS variables

## Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | Top bar | Email and phone number |
| 2 | Header / Menu | Logo and navigation links |
| 3 | Hero | Large banner with "Building Drawings" heading |
| 4 | Features | Three highlight boxes below the banner |
| 5 | Services | Basic & Common Repairs, Brake Repairs & Services, Preventive Maintenance |
| 6 | Projects | Eight "Alex Complex for Residence" cards with hover overlay |
| 7 | Counters | Projects, clients, tasks, coffee, professionals |
| 8 | Why we are the best | Six reason boxes |
| 9 | Testimonials | Client reviews |
| 10 | We Believe in Quality | Two big blog posts and four small ones |
| 11 | Footer | About, quick links and contact details |

## Project Structure

```
construction-website/
├── index.html     # The whole website (HTML + internal CSS)
└── README.md      # This file
```

## How to Run

1. Download or copy `index.html` into a folder.
2. Double-click `index.html` to open it in any browser (Chrome, Edge, Firefox, Safari).
3. An internet connection is needed to load the images and the Google font.

To edit, open `index.html` in any code editor such as VS Code or Notepad++.

## Contact Details Used

| Item | Value |
|------|-------|
| Phone | 0300 9260391 |
| Email | syedhasanshahqadri@gmail.com |

To change them, search for `0300 9260391`, `03009260391` and `syedhasanshahqadri@gmail.com` in `index.html` and replace every match. They appear in the top bar and the footer.

## Customization

### Change colours

At the top of the `<style>` block you will find:

```css
:root {
  --main: #f7631b;   /* orange accent colour */
  --dark: #222222;   /* headings, header text, footer background */
  --text: #777777;   /* body text */
  --light: #f9f9ff;  /* light section background */
}
```

Change these four values and the whole site updates.

### Change images

Every image uses an `<img src="...">` tag or a `url(...)` in CSS. Replace the link with any image URL you like.

Themed construction placeholders can be used like this (change `lock` for each image so they differ):

```
https://loremflickr.com/600/420/construction?lock=1
```

Or use your own pictures: put them in an `images/` folder next to `index.html` and write `src="images/my-photo.jpg"`.

### Change text

All headings and paragraphs are plain HTML. Search for the text you want to change and edit it directly.

### Add a new project card

Copy one `<div class="item">...</div>` block inside the Projects section, then change the image link and text.

## Browser Support

Works in all modern browsers: Chrome, Edge, Firefox, Safari and mobile browsers.

## Known Limitations

- No JavaScript, so there is no image slider, mobile hamburger menu or animated counters.
- The contact section only shows details; there is no working contact form (a form needs a backend).
- Images depend on an internet connection.

## Credits

- Design inspiration: [Colorlib](https://colorlib.com) free Construction template, licensed CC BY 3.0
- Font: [Poppins](https://fonts.google.com/specimen/Poppins) from Google Fonts
- Placeholder images: [Picsum Photos](https://picsum.photos)

## License

Free to use for personal and commercial projects. If you share it publicly, please keep the credit to Colorlib as required by the CC BY 3.0 license.# CONSTRUCTION-WEB
