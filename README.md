# Turret — Advanced Testimonials Grid

A sophisticated, visually structured testimonial section designed to showcase client feedback with elegance and clarity. Features a modular card layout with dual-background styling, brand integration, and responsive design.

---

## Live Preview

[View Live Demo](https://thisislefa.github.io/Turret)

---

## Features

- **Dual-Layer Card Design**: Separate visual zones for quotes and profiles with distinct background colors
- **Brand Integration**: Client logos with SVG icons and company association
- **Responsive Grid**: Adapts from 2-column desktop to single-column mobile layout
- **Typography Hierarchy**: Uses Poppins (headings) and Inter (body) for optimal readability
- **Hover Enhancements**: Subtle interactive effects on cards
- **Semantic Structure**: Clean HTML with ARIA-friendly markup
- **Customizable Theme**: CSS variables for easy color and spacing adjustments

---

## Project Structure

```
turret/
├── index.html          # Main HTML structure
├── style.css           # Complete styling with CSS variables
└── README.md           # This documentation
```

---

## Quick Start

1. Clone or download the project files.
2. Ensure `style.css` is in the same directory as `index.html`.
3. Open `index.html` in a browser or deploy to your hosting service.

---

## Customization

### Update Content
- Modify the `.section-title` in the header
- Replace client names, titles, and testimonials
- Update avatar image URLs (currently using Unsplash)
- Adjust brand logos and company names

### Theming
Edit the CSS variables in `:root` to match your brand:

```css
:root {
    --color-text-dark: #1a1a1a;
    --color-background-body: #ededed;
    --color-card-main-bg: #ffffff;
    --color-quote-block-bg: #f4f4f4;
    --card-border-radius: 15px;
    /* ... */
}
```

### Add More Testimonials
Duplicate a `.testimonial-card` block and update content accordingly.

---

## Responsive Behavior

- **Desktop**: 2-column grid
- **Tablet (< 992px)**: 1-column stacked layout
- **Mobile (< 600px)**: Compact padding, stacked profile/logo blocks

---

## Browser Support

Compatible with modern browsers supporting:
- CSS Grid & Flexbox
- CSS Custom Properties (variables)
- SVG rendering

---

## License

Free for personal and commercial use. Attribution is appreciated but not required.

---

## Maintainer

**Lefa Mofokeng**  
[github.com/thisislefa](https://github.com/thisislefa)

---

## Credits

- **Fonts**: [Poppins](https://fonts.google.com/specimen/Poppins) & [Inter](https://fonts.google.com/specimen/Inter)
- **Images**: [Unsplash](https://unsplash.com)
- **Icons**: Custom SVGs for brand logos
- **Design**: Modular testimonial grid concept

---

> **Turret** — A structured, elevated way to present feedback and build trust.


