# Stock Market Mastery Landing Page

A responsive landing page for **Stock Market Mastery**, a **JohnsonRich & Co. Ltd Program**.

This project is designed to present the program clearly, showcase its benefits, display real testimonial screenshots, and drive conversions through a direct WhatsApp enrollment link.

## Overview

The website helps potential students:

- understand what the program is about
- see who the program is for
- review the full module structure
- view testimonials and results
- check program details and pricing
- enroll directly through WhatsApp

## Features

- Responsive landing page design
- Clean and modern UI
- Sticky header navigation
- Smooth scrolling navigation
- WhatsApp call-to-action buttons
- Program details and pricing section
- Testimonial screenshot gallery
- Click-to-open testimonial lightbox popup
- Accessible structure with semantic HTML
- Mobile-friendly layout

## Project Structure

```bash
stock-market-mastery/
│
├── index.html
├── README.md
│
├── css/
│   └── main.css
│
└── media/
    ├── logo.jpeg
    ├── testimonial-1.jpeg
    ├── testimonial-2.jpeg
    ├── testimonial-3.jpeg
    ├── testimonial-4.jpeg
    └── testimonial-5.jpeg
````

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript
* Google Fonts
* Font Awesome Icons

## Sections Included

* Hero Section
* About the Program
* What the Stock Market Is
* Who the Program Is For
* Learning Outcomes
* Program Modules
* Included Benefits
* Testimonials / Results
* Pricing
* Final Call to Action
* Footer Contact Section

## WhatsApp Enrollment Link

The project uses this enrollment link:

```text
https://wa.link/mjpqyn
```

All buttons with the class below are automatically assigned that link:

```html
.whatsapp-link
```

## Testimonial Lightbox

The testimonial section supports image popup preview.

When a visitor clicks on a testimonial image:

* the image opens in a fullscreen popup
* clicking outside closes it
* clicking the close button closes it
* pressing `Esc` closes it

## How to Use

### 1. Clone or Download the Project

```bash
git clone https://github.com/your-username/your-repository-name.git
```

Or simply download the ZIP and extract it.

### 2. Open the Project

Open `index.html` in your browser.

### 3. Edit Content

You can update:

* text content inside `index.html`
* styles inside `css/main.css`
* images inside the `media/` folder
* WhatsApp link inside the JavaScript section of `index.html`

## Customization Guide

### Change the Program Name

Edit the text inside `index.html` wherever the program title appears.

### Change the WhatsApp Link

Inside the script at the bottom of `index.html`, update this line:

```javascript
const whatsappURL = "https://wa.link/mjpqyn";
```

### Replace Testimonial Images

Put your new images inside the `media/` folder and keep the same file names, or update the image paths in `index.html`.

### Change Colors

Update the CSS variables in `main.css`:

```css
:root {
  --primary-color: #f59e0b;
  --primary-dark: #d97706;
  --text-color: #111827;
}
```

## Deployment

You can deploy this project easily using:

* GitHub Pages
* Netlify
* Vercel
* cPanel hosting
* Any static web hosting service

## GitHub Pages Deployment

If deploying with GitHub Pages:

1. Push the project to a GitHub repository
2. Go to the repository settings
3. Open **Pages**
4. Choose the main branch
5. Save and wait for deployment

## Notes

* Ensure all testimonial image paths are correct
* Keep file names consistent to avoid broken images
* For best performance, optimize images before upload
* Test the site on both desktop and mobile before publishing

## Credits

* **Program Owner:** JohnsonRich & Co. Ltd
* **Development:** KD Global (https://www.kdevglobal.com/)

## License

This project is for client/business use.
Do not redistribute or resell without permission.
