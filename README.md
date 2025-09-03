# Configo-Project
Configo Project consists of LOGIN + BRANDING Page and this will further transform into entire website after implementation of JS and Backend
A responsive login page design for Configo, built with HTML5 and CSS.
The layout follows a modern split-screen design:

Laptop/Tablet → Left: Login Form | Right: Branding Section

Mobile→ Top: Login Form | Bottom: Branding Section

## Built With
HTML5 – Page structure

CSS3 – Styling and responsiveness

Google Fonts (Poppins) – Font family

## Key Features
- Responsive Layout with flexbox and media queries

- Login Section with inputs, button, and links

- Branding Section with gradient background + overlay (::after)

- Hover Effects for interactivity

- Positioning using relative + absolute for overlays

## Page Structure

A) Login Section (left on desktop, top on mobile)

Title & subtitle

Email and password inputs

Login button with hover effect

Forgot password / terms links



B) Branding Section (right on desktop, bottom on mobile)

Gradient background with overlay

Marketing message / tagline
## Styles

A) Main Styles (styles.css)

→Flexbox Layout: Used to divide the page into left and right halves.

→Left Section: Contains logo, signup button, login form, and terms.

→Right Section: Gradient background with overlay logo graphic and marketing message.

→Form Styling: Inputs, labels, and buttons styled with hover/focus states.

→Tooltip: Signup button shows a hover tooltip (Sign up only via Invitation).

→Extras: Subtle hover effects for links and inputs.


B) Utilities (utilities.css)

Utility classes to quickly apply common properties:

.d-flex → Display flex

.d-flex-col → Flex column layout

.justify-content-center → Horizontal centering

.align-items-center → Vertical centering

.text-black, .text-white, .text-muted → Text color helpers

.text-decoration-none → Removes underline from links

## Responsive Behavior

A) Desktop / Laptop (> 991px) → Split screen (Login left, Branding right)

B) Tablet (769px – 990px) → Split screen but tighter spacing

C) Mobile (≤ 768px) → Stacked vertically (Login on top, Branding below)
