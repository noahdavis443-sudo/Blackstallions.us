# Black Stallions LP — Website

A simple 4-page static site: Home, About, Services, Contact.

## Before you deploy — fill in your real details

Search each HTML file for anything in `[brackets]` and replace it with your real information:

- `[Your Phone Number]`
- `[Your Email]` / `[Your Email Address]`
- `[Your Business Address]`
- `[Your MC Number]` and `[Your DOT Number]`
- `[X]+` stat placeholders (years in business, fleet size, states served)
- The "Our Story" paragraph in `about.html`
- The third service card in `services.html`

## Contact form

The form in `contact.html` currently points to a placeholder Formspree URL
(`https://formspree.io/f/YOUR_FORM_ID`). It will not send you anything until
you create a free account at https://formspree.io, create a form, and swap
in your real form ID. This is covered in the deployment walkthrough.

## Running it locally

No build step needed — these are plain HTML/CSS/JS files. Open `index.html`
directly in a browser, or serve the folder with any static server.

## Deploying

See the step-by-step Vercel deployment walkthrough provided alongside this
file.
