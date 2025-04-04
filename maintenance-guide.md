# Maintenance Guide

## Updating Content

### Text Updates
1. Open the relevant HTML file
2. Locate the text content within `<p>` or `<h1>` tags
3. Update the text while maintaining the HTML structure
4. Save the file

### Adding New Pages
1. Copy an existing game page from the `games` folder (e.g., `games/game1.html`)
2. Rename the file (e.g., `games/game11.html`)
3. Update the content:
   - Title
   - Game information
   - Description
   - Image source
4. Add the new game to the catalog page (`catalog.html`)
5. Make sure to use correct path to style.css: `../style.css`

### Adding Images
1. Place new image files in the `images` folder
2. Use the following format for image names:
   - `game-name.jpg` for JPG images
   - `game-name.jpeg` for JPEG images
   - `game-name.png` for PNG images
   - `game-name.webp` for WebP images
   - Use lowercase and hyphens
3. Update image references in HTML:
   ```html
   <img src="../images/game-name.jpg" alt="Game Title">
   ```
   Note: Use `../images/` for game pages and `images/` for main pages

### Creating Links
Use the following format for internal links:
```html
<a href="page.html">Link Text</a>
```

For links to game pages:
```html
<a href="games/game1.html">Game Title</a>
```

## GitHub Pages Deployment
1. Create a new repository on GitHub
2. Upload all project files
3. Go to repository Settings
4. Navigate to Pages section
5. Select main branch as source
6. Save changes
7. Wait for deployment (usually takes a few minutes)

## File Structure
```
/
├── index.html
├── catalog.html
├── contact.html
├── style.css
├── games/
│   ├── game1.html
│   ├── game2.html
│   ├── game3.html
│   ├── game4.html
│   ├── game5.html
│   ├── game6.html
│   ├── game7.html
│   ├── game8.html
│   ├── game9.html
│   └── game10.html
├── images/
│   ├── last-of-us.jpg
│   ├── fifa23.jpeg
│   ├── gow-ragnarok.jpeg
│   ├── cyberpunk.png
│   ├── spiderman.jpg
│   ├── re8.jpeg
│   ├── ac-valhalla.jpg
│   ├── gt7.webp
│   ├── horizon.jpg
│   └── elden-ring.jpg
├── sitemap.md
├── wireframes.md
└── maintenance-guide.md
``` 