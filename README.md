# Frontend Mentor - Testimonials grid section solution

This is a clean, responsive, and modern solution to the Testimonials grid section challenge on Frontend Mentor.

## Links

- Solution URL: [https://github.com/veon321/Testimonials-grid-section](https://github.com/veon321/Testimonials-grid-section)
- Live Site URL: [https://veon321.github.io/Testimonials-grid-section/](https://veon321.github.io/Testimonials-grid-section/)

## Built with

- **Semantic HTML5 markup:** Structured using appropriate landmark elements (`<main>`) and structural block nodes (`<article>`) to represent independent, self-contained review entities while maintaining high accessibility (WCAG).
- **CSS Custom Properties (Variables):** Implemented for robust token management, governing the strict color palette defined by the design spec (Primary Purples, Neutrals, and varying Grey values).
- **CSS Grid Layout:** Employed as the primary macro-layout engine to orchestrate the multi-column asymmetrical grid structure, handling complex two-dimensional component mapping seamlessly.
- **Flexbox Layout:** Utilized inside individual card components for micro-layout positioning, enabling fluid vertical stacking of content and precise horizontal alignment within user profile blocks.
- **Responsive Web Design:** Built using a mobile-first philosophy combined with explicit grid-line definitions to ensure structural adaptation across varying screen dimensions.

## Features

- **Asymmetrical Grid Orchestration:** Utilizes explicit grid-line spanning (`grid-column: span 2`, `grid-row: span 2`) and explicit cell targeting to flawlessly match the intricate desktop "bento-style" layout architecture.
- **Robust Component Encapsulation:** Isolates each testimonial card inside independent `<article>` wrappers, preventing document-tree bleeding and ensuring style encapsulation.
- **Dynamic Profile Typography Mapping:** Leverages layered opacity scaling on secondary text blocks (`.status`, `.description`) to guarantee deep typographical contrast and adherence to precise readability standards.
- **Fluid Viewport Adaptation:** Implements a single, non-destructive media query breakpoint that dynamically collapses the complex 4-column matrix into a single-column layout for optimal readability on mobile screens.
- **Decorative Asset Masking:** Integrates vector design patterns (`bg-pattern-quotation.svg`) via layered CSS background properties, utilizing precise positioning constraints to maintain alignment without cluttering the HTML DOM tree.
