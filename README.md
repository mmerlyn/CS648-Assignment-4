# CS648 Assignment 4 - CSS Grid Layout Practice

_This project demonstrates CSS Grid Layout, including grid template areas, nested grids, and alignment properties through three different page layouts._

## Overview

This assignment focuses on recreating three specific layouts using **CSS Grid Layout**. Each layout showcases different grid techniques with increasing complexity.

## Layouts Implemented

### Layout 1: Product Showcase Grid

- 4-column x 4-row grid structure
- Company logo and navigation header
- Full-width featured product image
- Two product cards displayed side-by-side
- Footer section

### Layout 2: Content Grid with Article Feed

- 4-column x 4-row outer grid
- Company logo and navigation header
- Large hero section with Lorem Ipsum content
- **Nested 3x3 grid** of content boxes (9 items)
- Demonstrates grid-within-grid technique
- Footer section

### Layout 3: Mixed Content Layout

- 4-column x 6-row grid (most complex)
- Company logo and navigation header
- Hero header section
- Two title sections
- Two blog post sections spanning multiple columns
- Four featured products in a 2x2 arrangement
- Footer section

## CSS Grid Properties Used

- `display: grid` - Enable grid layout
- `grid-template-columns` - Define column tracks with `1fr`, `2fr`, and fixed units
- `grid-template-rows` - Define row tracks with explicit heights
- `grid-template-areas` - Named grid regions for semantic layout
- `grid-area` - Assign elements to named areas
- `grid-gap` / `gap` - Spacing between grid cells (18px-22px)
- `repeat()` - Create uniform grid tracks
- `justify-items` - Horizontal alignment within cells
- `align-self` - Vertical alignment of individual items
- `align-content` - Content alignment within the grid

## Techniques

1. **Named Grid Areas**: Semantic layout definition using `grid-template-areas`

   ```css
   grid-template-areas:
     "logo empty navi navi"
     "feat feat feat feat"
     ...;
   ```

2. **Nested Grids**: Grid containers inside grid items (Layout 2's 3x3 content grid)

3. **Fractional Units**: Responsive column sizing with `1fr` and `2fr`

4. **Navigation as Grid**: `nav ul` styled as a 4-column grid

5. **Fixed-Width Centered Layout**: `max-width: 960px` with `margin: auto`

## Technologies

- HTML5
- CSS3 (CSS Grid Layout)
- No JavaScript or frameworks

## Learnings

- CSS Grid Layout syntax and properties
- Grid container and grid item relationships
- Precise layout positioning with grid areas
- Nested grid implementations
- Maintainable and semantic CSS code

---

**Course:** CS 648 - Modern Web Development Frameworks<br>
**University:** San Diego State University (SDSU)<br>
**Author:** Merlyn Mercylona M
