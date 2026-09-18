# COPPERLEAF ELECTRICAL - WEDE5020 POE Part 2

Student: Maloka Thakgalang ST 10512359
Module: WEDE5020 - Web Development
Part: Part 2 - Styling and Responsive Design

## Project Overview
CopperLeaf Electrical is a responsive website for an electrical services company. Part 2 focuses on external CSS styling, responsive layouts, and visual design improvements from the Part 1 wireframes.

Live site showcases: Home, About, Services, Enquiry, and Contact pages.

## Features Implemented (Part 2 Requirements)

### 1. External Stylesheet
- Single external file: `css/style.css` linked to all HTML pages
- Includes reset, base typography, and global variables

### 2. Selectors & Styling
- **Base**: body, h1-h3, p, a with Copperleaf brand colours #061a2f (navy) and gold #c9a86a
- **Layout**: Flexbox for header/navigation, CSS Grid for services (3 columns desktop)
- **Cards**: Rounded corners (12px), soft shadows, hover effects
- **Pseudo-classes**: `a:hover`, `button:hover`, `input:focus`, `nav a.active`

### 3. Responsive Design
- Desktop: 1200px+ (3 column grid)
- Tablet: 1024px (2 columns, collapsed nav)
- Mobile: 768px and 480px (single column, hamburger menu, stacked layout)
- Banner images use `object-fit: cover` with fixed height 500px on contact/enquiry

### 4. Visual Enhancements
- Consistent header/footer across all pages
- Form styling for enquiry and contact forms with validation styling
- Images optimized in `/images` folder

## File Structure
