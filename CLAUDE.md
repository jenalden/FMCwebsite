# Church of the First Mark Website

## Project Overview
This is the website for the Church of the First Mark, a church centered around human creativity as a spiritual practice. The tagline is "making stuff is sacred actually".

## File Locations

### Website Repository
- Main site location: `C:\Users\jenal\Documents\GitHub\FMCwebsite`
- GitHub repository with CNAME pointing to custom domain

### Source Assets
- Main folder: `C:\Users\jenal\Google Drive\Church of the First Mark`
- Website content: `C:\Users\jenal\Google Drive\Church of the First Mark\Website`
- Branding assets: `C:\Users\jenal\Google Drive\Church of the First Mark\Logos and Collateral`

### Key Assets
- **Font**: Lindum (Regular) - `C:\Users\jenal\Google Drive\Church of the First Mark\Logos and Collateral\Lindum Font\Lindum-Regular.ttf`
- **Background**: wood.jpg - `C:\Users\jenal\Google Drive\Church of the First Mark\Website\images\wood.jpg`
- **Content**: About.md - `C:\Users\jenal\Google Drive\Church of the First Mark\Website\About.md`
- Other images available: wall.jpg, carpet.jpg

## Site Structure

### Pages
1. **index.html** - Home/Landing page
   - Features church name in Lindum font
   - Tagline: "making stuff is sacred actually"
   - Simple, centered design

2. **about.html** - About page
   - Full content from About.md
   - Explains the church's philosophy, stewards, and domains
   - Contains three key links:
     - Link to First Day of Making page
     - Link to Events page
     - Link to Donate page

3. **events.html** - Events/Calendar page
   - Simple page saying "Join us for our First Day of Making"
   - Links to First Day of Making page

4. **donate.html** - Donations page
   - Placeholder for donation information

5. **first-day-of-making.html** - First Day of Making event page
   - NOT in main navigation (only linked from About and Events)
   - Event date: March 7, 2026
   - Placeholder for event details

### Navigation
Main menu includes:
- Home
- About
- Events
- Donate

Note: First Day of Making page is intentionally NOT in the main menu.

## Design Specifications

### Colors
- **Background**: Wood texture image (warm brown tones)
- **Text**: Charcoal grey (#2a2a2a) - high contrast but not pure black
- **Secondary text**: #4a4a4a
- **Navigation bar**: Semi-transparent brown (rgba(139, 90, 60, 0.95)) - beige text (#f5f5dc)
- **Content boxes**: Semi-transparent beige (rgba(245, 245, 220, 0.9-0.95))
- **Links**: Brown (#8b5a3c) with darker hover state (#6b4a2c)

### Typography
- **Title font**: Lindum (custom font, loaded via @font-face)
- **Body font**: Georgia, serif
- **Title size**: 4rem desktop, 2.5rem mobile
- **Tagline size**: 1.5rem desktop, 1.2rem mobile
- **Body text**: 1.1rem desktop, 1rem mobile

### Responsive Design
- Mobile-first approach (most users will access on mobile)
- Breakpoint at 768px for mobile vs desktop
- Navigation wraps on smaller screens
- Flexible padding and font sizes
- Content boxes adjust width and padding

## Content Structure

### About Page Sections
1. Why a church?
2. What is this church all about?
3. Why is it called the Church of the First Mark?
4. How can I get involved?
   - Come to a service (First Day of Making - March 7, 2026)
   - Host an event
   - Donate
5. Who is behind this idea?
   - Jennifer Kesteloot - Steward of Forms
   - Eneasz Brodski - Steward of Narrative
   - Hannah Aldern - Steward of the Hearth
6. What are Stewards?
7. What are Domains?
   - Domain of Forms (visual art)
   - Domain of Narrative (storytelling)
   - Domain of the Hearth (domestic arts)
   - Domain of Mechanica (emerging technologies)

## Technical Notes

### Font Loading
Using file:/// protocol to load local font file from Google Drive location. This works for local development but will need to be updated for production deployment.

### Background Image
Using file:/// protocol to load wood.jpg. Same consideration as fonts - will need proper path for production.

### Future Considerations
- Images for stewards (currently marked as "image tbd")
- Detailed content for First Day of Making page
- Donation information and payment integration
- Calendar system for events
- Potentially move assets to web-accessible location for production

## Design Philosophy
- Clean, simple, cohesive design
- Colors pulled from wood background for visual harmony
- High readability with proper contrast
- Mobile-responsive (primary audience on mobile)
- Focus on content over decorative elements
- Warm, welcoming aesthetic that reflects the handmade/creative focus
