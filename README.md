# AccounTax Solution Website

A modern, responsive static website for AccounTax Solution(accountaxsolution.in), built with HTML5, Bootstrap 5, and vanilla JavaScript. The site is designed for accountants and tax professionals, featuring dynamic content, animated stats, and contact forms suitable for static hosting (e.g., GitHub Pages).

## Features

- Responsive design using Bootstrap 5
- Animated stats counters powered by GSAP (GreenSock Animation Platform)
- Scroll and reveal animations using AOS (Animate On Scroll)
- Image galleries and lightboxes via GLightbox
- Swiper.js for testimonials carousel
- Contact form with mailto: handler (no backend required)
- All content and contact info managed via constants for easy updates
- Vendor folder for third-party JS/CSS libraries
- Social media links and Google Maps integration

## Getting Started

1. **Clone the repository**
   ```sh
   git clone https://github.com/gra-viity/accounTaxSolutions.git
   ```
2. **Open the project folder** in your code editor or deploy to your static hosting provider (e.g., GitHub Pages).
3. **No build step required.** All files are ready to use as-is.

## Folder Structure

```
accounTaxSolutions/
├── index.html
├── portfolio-details.html
├── service-details.html
├── starter-page.html
├── assets/
│   ├── css/
│   │   └── main.css
│   ├── js/
│   │   └── main.js
│   ├── img/
│   └── vendor/
│       ├── bootstrap/
│       ├── bootstrap-icons/
│       ├── aos/
│       ├── glightbox/
│       ├── swiper/
│       ├── imagesloaded/
│       ├── isotope-layout/
│       └── ...
├── forms/
│   ├── contact.php (legacy, not used)
│   └── newsletter.php (legacy, not used)
└── README.md
```

## How It Works

- **Stats Counters:**
  - GSAP animates the numbers in the stats section when they come into view.
  - No PureCounter dependency; all animation is handled by GSAP.
- **Contact Form:**
  - Uses a mailto: link to open the user's email client with pre-filled details.
  - No backend or third-party service required.
- **Animations:**
  - AOS is used for scroll-based reveal effects.
  - GLightbox and Swiper.js provide gallery and carousel functionality.

## Customization

- Update contact info and constants in `assets/js/constants.js` (if present).
- Change images in `assets/img/` as needed.
- Edit content in `index.html` and other HTML files for your needs.

## Deployment

- Host on any static site provider (GitHub Pages, Netlify, Vercel, etc.).
- No server-side code required.

## Credits

- Bootstrap 5
- Bootstrap Icons
- GSAP (GreenSock Animation Platform)
- AOS (Animate On Scroll)
- GLightbox
- Swiper.js
- ImagesLoaded
- Isotope Layout

## License

This project is released under the MIT License. See `LICENSE` for details.

---

For questions or support, contact: accountaxsolutions@gmail.com