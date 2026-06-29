# Claude Code Instructions -- Cabin Build Docs

## File conventions
- One HTML file per building system, named with hyphens (e.g. roof-assembly.html)
- All pages share styles.css -- never use inline styles except for SVG diagrams
- All pages link back to index.html in the header nav
- Cross-references between pages use relative links with descriptive anchor text

## Section template for every system page
Every system page must have these sections in this order:
1. Status (one of: Decided / In Progress / Open)
2. Overview (2-3 sentence summary)
3. Materials & Specs
4. Installation Notes
5. Open Items
6. Dependencies (links to related system pages)

## Updating pages
- When updating a system page, do not alter the structure of other pages
- When an open item is resolved, move it to the Decisions section with a plain-language note on why
- Keep the index.html open items summary in sync when system pages change

## Diagrams
- Diagrams are inline SVGs embedded directly in the relevant system page
- Use simple, labeled line drawings -- no decorative styling
- SVGs should have a white background and print cleanly

## Print support
- styles.css includes a print stylesheet
- Navigation and status badges should be hidden on print
- Each section should avoid breaking across pages where possible
