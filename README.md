# Bright Paths Tutoring — Website

A polished single-page website for a tutoring/education matching service based on the Sunshine Coast, Queensland, Australia.

## What Was Built

A complete, responsive, single-page website (`index.html`) with embedded CSS and JavaScript. No frameworks or build tools required — just open the file in a browser or deploy to any static hosting.

### Sections
1. **Hero** — Warm headline, trust badges, dual CTA buttons, gradient background accents
2. **About / Why Us** — Split layout with decorative card stack and feature list (homeschooling, learning differences, general support)
3. **What We Offer** — Three service cards (Reading & Literacy, Writing & Spelling, Mathematics) with SVG icons, descriptions, and topic tags
4. **How It Works** — Three-step process with connected progress line and numbered emoji icons
5. **Online vs In-Person** — Side-by-side comparison cards with benefit checklists
6. **Parent Intake Form** — Comprehensive form with all requested fields including:
   - Parent/guardian details (name, email, phone)
   - Child details (name, age/year level)
   - Support areas (checkboxes with conditional "Other" field)
   - Learning needs/diagnoses textarea
   - Goals for tutoring
   - Format preference (radio: Online / In-Person / Either) with conditional suburb field
   - Day/time availability grid (Mon–Sun × Morning/Afternoon/Evening)
   - Referral source dropdown
   - Additional information textarea
   - Client-side validation with friendly error messages
   - Formspree POST endpoint (placeholder: `https://formspree.io/f/xcontact`)
7. **Footer** — Branding, quick links, contact info, copyright

### Design
- **Pastel palette**: sage green (#B8D4C8), warm peach (#F5D5C8), light lavender (#D8D0E8), cream (#FFF8F0), sky blue (#C8DFF5)
- **Fonts**: Nunito (headings) + Open Sans (body) via Google Fonts
- **Responsive**: Mobile-first, works on all screen sizes
- **Animations**: Fade-in on scroll using IntersectionObserver
- **Accessibility**: Semantic HTML, proper labels, ARIA attributes, keyboard-navigable

### Technical Details
- Pure HTML/CSS/JS — no dependencies
- Single file deployment
- ~60KB total (HTML + embedded CSS + JS)
- Custom SVG icons throughout
- Smooth scroll navigation with fixed header
- Mobile hamburger menu with animation

### To Deploy
Upload `index.html` to any static hosting (Netlify, Vercel, GitHub Pages, etc.). Update the Formspree endpoint in the form action attribute when ready.
