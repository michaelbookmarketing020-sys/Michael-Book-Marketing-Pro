# Michael | Professional Book Marketing Website

A premium, editorial, multi-page marketing website for Michael, a professional book marketer with over eight years of experience helping authors build visibility, reach relevant readers, and market their books strategically.

Built with semantic HTML5, modern CSS3, and vanilla JavaScript. No frameworks. No build step. Open and go.

---

## Table of Contents

1. Project Overview
2. Project Structure
3. Pages Included
4. Brand Identity
5. Fonts
6. Logo
7. Images (Sourcing Guide)
8. Local Setup
9. Deployment
10. Formspree Contact Form
11. Editable Pricing Placeholders
12. Animations and Accessibility
13. SEO and Performance
14. Browser Support
15. Manual Tasks Checklist
16. Things That Have Not Been Verified
17. Contact

---

## 1. Project Overview

This website presents Michael's professional book marketing services across six separate pages, each with its own content, layout, and purpose. It is designed to communicate experience, trust, craft, and strategic thinking in the book publishing and marketing industry.

**Key figures used across the site:**

- 8+ years of professional book marketing experience
- 150+ authors worked with
- 400+ books promoted
- 500+ readers reached
- 20 authors who achieved bestseller status

No other statistics, awards, certifications, or client names have been invented.

---

## 2. Project Structure

```
MICHAEL-BOOK-MARKETING/
│
├── index.html           Homepage
├── services.html        Services page (7 categories)
├── about.html           About Me page
├── faq.html             FAQ page (accordion)
├── pricing.html         Pricing page (3 packages)
├── contact.html         Contact Me page (Formspree)
├── style.css            Complete shared stylesheet
├── my logo.png          Your logo (to be placed here)
├── images/              All sourced website images
└── README.md            This file
```

No frameworks, no build tools, no package manager, no additional folders.

---

## 3. Pages Included

| Page | File | Logo Displayed |
|------|------|----------------|
| Home | `index.html` | Yes |
| Services | `services.html` | No |
| About Me | `about.html` | Yes |
| FAQ | `faq.html` | No |
| Pricing | `pricing.html` | No |
| Contact Me | `contact.html` | Yes |

Navigation across every page uses the labels: **Home | Services | About Me | FAQ | Pricing | Contact Me**, with the active page clearly indicated.

---

## 4. Brand Identity

Three brand colours are used throughout the site and defined as CSS custom properties in `style.css`:

| Colour | Hex | Role |
|--------|-----|------|
| Midnight Navy | `#142536` | Authority, depth, dark sections, headings |
| Warm Ivory | `#F5F0E6` | Background, editorial reading surface |
| Muted Gold | `#B69A62` | Refined accents, eyebrows, buttons, underlines |

Supporting tonal variations (navy-deep, navy-soft, ivory-warm, ivory-deep, gold-light, gold-deep) are also defined for layered visual depth.

---

## 5. Fonts

Loaded via Google Fonts in every HTML page:

- **Cormorant Garamond** (serif) — all headings, eyebrows, decorative numerals
- **Inter** (sans-serif) — body text, navigation, buttons, labels

The combination creates an editorial, publishing-inspired feel appropriate to the book industry.

---

## 6. Logo

- Filename: **`my logo.png`** (exact, including the space)
- Location: project root (same folder as the HTML files)
- Displayed on: Home, About Me, Contact Me
- Not displayed on: Services, FAQ, Pricing (brand wordmark only)

The logo is also referenced as the favicon for every page.

**Action required:** Place your `my logo.png` file in the project root. Do not rename it. The code already references this exact filename.

---

## 7. Images (Sourcing Guide)

All website images (other than the logo) should be placed in the `images/` folder. Suggested sources: **Unsplash**, **Pexels**, **Pixabay**. All three permit free commercial use. Choose high-quality, relevant images that reflect books, publishing, literature, reading, and marketing.

### Required image filenames

Save each downloaded image using the **exact filename** below so the HTML references work without modification.

**Homepage (`index.html`)**

| Filename | Suggested subject |
|----------|-------------------|
| `hero-library.jpg` | An elegant library or bookshelves, warm literary atmosphere |
| `author-desk.jpg` | A writer's desk with notebook, books, coffee, or similar still life |
| `service-branding.jpg` | Book cover design materials, typography, or print proofs |
| `service-advertising.jpg` | A laptop with analytics or an advertising dashboard |
| `service-readers.jpg` | A reader or small group of readers with books |
| `service-amazon.jpg` | Someone browsing books on a laptop or tablet |

**Services page (`services.html`)**

| Filename | Suggested subject |
|----------|-------------------|
| `cat-branding.jpg` | Book cover concepts or branding materials on a designer's desk |
| `cat-advertising.jpg` | Analytics dashboard, charts, or ad campaign visuals |
| `cat-readers.jpg` | Readers in a community or book club setting |
| `cat-amazon.jpg` | Laptop screen with Amazon KDP or keyword research |
| `cat-brand.jpg` | Author website on a laptop next to notebook and pen |
| `cat-publicity.jpg` | A podcast microphone next to a book |
| `cat-strategy.jpg` | A detailed strategy plan, calendar, and notes |

**About page (`about.html`)**

| Filename | Suggested subject |
|----------|-------------------|
| `about-books.jpg` | A thoughtful arrangement of books with a notebook and pen in natural light |
| `about-commitment.jpg` | An open book with handwritten notes beside a stack of hardcover titles |

### Image guidance

- Use natural, editorial, warm-toned photography where possible to match the Warm Ivory palette.
- Avoid heavy filters, dated stock looks, watermarks, or distracting subjects.
- Target around 1600–2000 pixels wide for landscape images, and around 1200–1600 pixels wide for portrait images.
- Save as `.jpg` for photographs to keep file sizes small.
- Optimize before uploading using a tool such as [Squoosh](https://squoosh.app) or [TinyJPG](https://tinyjpg.com).

### Alternative text

All `<img>` tags already include descriptive `alt` attributes. If you choose images that differ noticeably from the suggested subjects, update the `alt` attribute in the corresponding HTML file to match the new image.

---

## 8. Local Setup

### Option A: Open directly

1. Clone or download the project folder.
2. Place `my logo.png` in the project root.
3. Place all sourced images in the `images/` folder using the exact filenames listed above.
4. Open `index.html` in any modern browser.

### Option B: Live Server in VS Code (recommended)

1. Open the project folder in VS Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and choose **Open with Live Server**.
4. The site opens in your browser and auto-reloads on file changes.

Live Server is recommended because the contact form AJAX submission works more reliably over `http://` than from a `file://` URL.

---

## 9. Deployment

This is a static website. Any static host will serve it without configuration.

**Easy options:**

- **Netlify** — drag and drop the folder at [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — connect a GitHub repository at [vercel.com](https://vercel.com)
- **GitHub Pages** — push to a repository and enable Pages in settings
- **Cloudflare Pages** — connect a GitHub repository at [pages.cloudflare.com](https://pages.cloudflare.com)

All of the above offer free hosting with HTTPS, which is important for the contact form to work smoothly.

---

## 10. Formspree Contact Form

The contact form on `contact.html` submits enquiries using your Formspree endpoint:

```
https://formspree.io/f/xyeeqogk
```

### How it works

- The form posts via AJAX using the Fetch API.
- Users remain on the contact page and see a success or error message in place.
- A honeypot field (`_gotcha`) is included to reduce spam.
- All six required fields are sent: Full Name, Email, Book Title, Book Genre, Service Required, Project Description.

### What you need to do

1. Log in to your Formspree account at [formspree.io](https://formspree.io).
2. Open the form linked to endpoint `xyeeqogk`.
3. Confirm that **email notifications** are enabled and sent to:
   `michael.bookmarketing020@gmail.com`
4. (Optional) Set up a **custom reply-to** so the sender's email address becomes the reply-to automatically.
5. (Optional) Enable Formspree's spam filtering features for additional protection.

### Verification test

**The form has not been submission-tested.** After deploying (or running via Live Server), send yourself one real test enquiry and confirm:

- The success message appears in the browser.
- The enquiry arrives in your Formspree inbox.
- The notification arrives in your Gmail inbox.

If anything does not work, check your Formspree dashboard first for delivery status.

---

## 11. Editable Pricing Placeholders

On `pricing.html`, each of the three packages displays:

```html
<div class="pricing-price">$[Price]</div>
```

**To add your real prices:**

1. Open `pricing.html` in VS Code.
2. Press `Ctrl + F` (or `Cmd + F` on Mac).
3. Search for `$[Price]`.
4. Replace each of the three instances with your actual price (for example, `$450`, `$1,200`, `$2,800`).
5. If you prefer a different currency symbol, change `$` to `£`, `€`, or any other symbol at the same time.

No other pricing text, discounts, or promotional claims appear anywhere on the site.

---

## 12. Animations and Accessibility

All animations are written in `style.css`. Interactive behaviour is handled by small, scoped inline scripts in each HTML file.

**Animation features:**

- Smooth scroll-reveal on sections, headings, and cards
- Hero entrance sequence with staggered fade-and-rise
- Slow background zoom on the hero image
- Elegant button hover fills
- Animated navigation underlines
- Smooth FAQ accordion expand/collapse
- Image hover zoom in service and category cards
- Mobile menu slide-in with staggered item reveal
- Animated scroll indicator line on the homepage hero

**Accessibility:**

- All animations respect `prefers-reduced-motion: reduce` and disable automatically for users with that system preference.
- ARIA labels on the mobile nav toggle and FAQ buttons.
- Visible focus outlines on all interactive elements using the brand gold colour.
- Semantic landmarks (`<header>`, `<nav>`, `<main>` via sections, `<footer>`).
- Descriptive `alt` text on every image.
- Sufficient colour contrast between text and background in all sections.

---

## 13. SEO and Performance

Each page includes:

- A unique `<title>` tag reflecting the page content
- A relevant `<meta name="description">`
- A concise `<meta name="keywords">`
- Proper heading hierarchy (one `<h1>` per page)
- Semantic HTML throughout
- Responsive viewport declaration
- Descriptive image `alt` attributes
- `loading="lazy"` on below-the-fold images
- `loading="eager"` on the homepage hero image
- Preconnect hints for Google Fonts

To improve performance further, make sure to optimize all images before placing them in the `images/` folder.

---

## 14. Browser Support

Tested design patterns work in all modern browsers:

- Chrome / Edge (latest)
- Firefox (latest)
- Safari (14+)
- Mobile Safari (iOS 14+)
- Chrome for Android (latest)

Internet Explorer is not supported.

---

## 15. Manual Tasks Checklist

Before launching the site, complete the following:

- [ ] Place `my logo.png` in the project root
- [ ] Download and save all images listed in Section 7 into the `images/` folder using the exact filenames
- [ ] Replace the three `$[Price]` placeholders on `pricing.html` with your real prices
- [ ] Log in to Formspree and confirm notifications are forwarded to `michael.bookmarketing020@gmail.com`
- [ ] Send one real test enquiry through the live contact form and confirm it arrives in your Gmail
- [ ] Review all page copy once and make any wording changes you prefer
- [ ] Deploy the site to Netlify, Vercel, GitHub Pages, or your preferred static host
- [ ] If using a custom domain, configure DNS with your hosting provider

---

## 16. Things That Have Not Been Verified

Full transparency about what has not been tested at build time:

- **The Formspree form has not been submission-tested.** The code and endpoint are correct, but a real user submission on the live site is required to confirm end-to-end delivery.
- **Images have not been downloaded.** The HTML correctly references the expected image filenames, but the actual image files need to be sourced from Unsplash, Pexels, or Pixabay and placed in the `images/` folder as described in Section 7.
- **The logo file has not been placed.** The HTML references `my logo.png` in the project root; the file itself must be added.
- **Live browser testing across physical devices** is not possible at build time. Please test on your own phone, tablet, and desktop after deploying.

---

## 17. Contact

**Michael**
Professional Book Marketing

Email: [michael.bookmarketing020@gmail.com](mailto:michael.bookmarketing020@gmail.com)

---

*This website was built with care, with attention to editorial typography, premium layout composition, and professional content, for a book marketing business that takes authors and their work seriously.*

© Michael. All rights reserved.