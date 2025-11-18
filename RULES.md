# AI Coding Assistant Rules for "Driving Class with Nas" Project

This file outlines the mandatory context, styling, and coding principles the assistant MUST follow when generating or modifying code for this project.

## 1. Project Context & Purpose

**Primary Goal:** The website's sole purpose is to serve as a high-conversion landing page for booking driving classes with the instructor, "Nas."

**Target Audience:** Nervous beginners, parents booking lessons for teens, and experienced drivers needing test prep. The tone should be reassuring, professional, and trustworthy.

**Key Calls-to-Action (CTAs):** All primary buttons must direct the user to "Schedule/Book a Lesson" or "Contact Nas."

**Tone:** Use friendly but professional language. Emphasize safety, patience, and personalized instruction.

## 2. Styling & Aesthetics (Tailwind CSS)

**Framework:** All styling MUST use Tailwind CSS classes and adhere to the following color palette and design principles.

**Font:** Use the 'Inter' font for all text.

**Design Elements:**

- **Corners:** All major elements (cards, buttons, containers) must have rounded corners (`rounded-xl` or `rounded-2xl`).
- **Shadows:** Use shadows liberally (`shadow-md`,`shadow-lg`, `shadow-xl`) to give elements depth and a clean, modern look.
- **Responsiveness:** All layouts must be fully responsive using Tailwind's standard breakpoints (`sm:`, `md:`, `lg:`). The design must look excellent on mobile devices first.

Mobile View
Sticky “Book Now” button visible at all times.

Vertical stacking for text and images.

Readable fonts ≥ 16 px.

Booking calendar fits one screen scroll.
## 3. Code Principles (Astro/HTML/JS)

**Client-Side Logic:** Use vanilla JavaScript. Avoid large frameworks unless explicitly requested by the user. JavaScript should be confined to the `<script>` tag within the HTML file.

**Asset Management:**

- **Images:** Use placeholder images (e.g., `https://placehold.co/`) or inline SVGs for simple icons. DO NOT use external image URLs for production assets.
- **Icons:** Prefer using simple SVG icons or a library like Lucide (if available in the Astro context) for clarity.

**Data Structure:**

- If lesson packages or pricing data are generated, they should be defined as clean JavaScript arrays of objects for easy manipulation.
- All hardcoded pricing must use the secondary/accent color (`#facc15`).

## 4. Key Content & Structure Requirements

The following sections are mandatory components of the generated page structure:

2. **Hero Section:** Must contain a strong CTA button using the secondary/accent color.

3. **About Nas:** A section dedicated to building trust, emphasizing experience, certification, and patience.

4. **Contact/Booking CTA Block:** A prominent, simple block with a final CTA and direct contact info (phone/email).

## 5. Additional Notes

- Always prioritize mobile-first design
- Ensure all CTAs are highly visible and use the accent color (#facc15)
- Maintain consistency with the color palette throughout
- Keep the tone friendly, professional, and reassuring
- Focus on conversion optimization - every element should guide users toward booking
