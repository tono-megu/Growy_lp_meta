# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a landing page for "Growy", a coaching service for middle school entrance exam preparation targeting working parents. The site is designed as a single-page application with a focus on conversions through LINE registration for free consultations.

## Development Commands

### Local Development Server
```bash
python3 -m http.server 8000
```
Then access `http://localhost:8000` to view the landing page.

## Architecture

### File Structure
- `index.html` - Main landing page with 10 distinct sections
- `style.css` - Complete responsive styling with mobile-first approach

### Design System
- **Color Palette**: Deep green theme using CSS custom properties
  - Primary: `#2e5945` (deep green)
  - Primary Light: `#4a7c59`
  - Primary Dark: `#1e3a2e`
  - Accent: `#7fbc83` (light green)
- **Typography**: Japanese-optimized font stack (Hiragino fonts)
- **Layout**: Mobile-first responsive design with breakpoints at 768px and 1024px

### Landing Page Structure
The page follows a conversion-optimized 10-section structure:
1. **Hero Section**: Main value proposition with social proof badges
2. **Problem Identification**: Pain points of working parents (checklist format)
3. **Risk Amplification**: Consequences of inaction
4. **Solution Presentation**: 3-feature breakdown of coaching service
5. **Process Flow**: 3-step user journey
6. **Social Proof**: Customer testimonials and achievement logos
7. **Expert Introduction**: Credibility building
8. **FAQ Section**: Common objections handling
9. **Closing/CTA**: Final conversion push with urgency
10. **Footer**: Legal and contact information

### Key Dependencies
- Font Awesome 6.0.0 (CDN) for icons
- No JavaScript frameworks - pure HTML/CSS implementation

### Responsive Behavior
- Mobile-first CSS with progressive enhancement
- Grid layouts transform from single-column (mobile) to multi-column (desktop)
- CTA buttons optimized for touch interfaces
- Typography scales appropriately across devices

### CTA Strategy
- Primary CTA: LINE registration buttons (green #06c755)
- Strategic placement: Hero section and closing section
- Consistent messaging focused on "free consultation"