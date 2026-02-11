# Personal Website

A clean, simple one-page website for showcasing your academic and professional background.

## GitHub Pages Deployment

1. Create a new repository on GitHub (e.g., `yourname.github.io` or `personal-site`)
2. Upload `index.html` and `styles.css` to your repository
3. Go to repository Settings > Pages
4. Under "Source", select your main branch and "/ (root)" folder
5. Click Save
6. Your site will be live at: `https://yourusername.github.io/repository-name/`

## Customization

### Update Your Information

Replace the following placeholder text:

1. **Name**: "Your Name" in the `<h1>` tag
2. **Title**: "[Your Field]" in the subtitle
3. **Email**: `your.email@example.com` in the Connect section
4. **Links**: Update LinkedIn and Substack URLs
5. **Content**: Replace all Lorem ipsum text with your actual information

### Replace Lorem Ipsum

Fill in your real information in these sections:
- About section
- Education entries (degrees, universities, dates)
- Experience entries (positions, companies, dates)

### Change Colors

Edit these values in `styles.css`:

```css
body {
    color: #2c2c2c;        /* Main text color */
}

a {
    color: #1a1a1a;        /* Link color */
    border-bottom: 1px solid #ccc;  /* Link underline */
}
```

### Change Fonts

The site uses:
- **Lora** for headings (serif)
- **Inter** for body text (sans-serif)

To change fonts, update the Google Fonts link in `index.html` and the font-family in `styles.css`.

## Files

- `index.html` - The complete website
- `styles.css` - All styling
- `README.md` - This file

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge).

