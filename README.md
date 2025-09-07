Overview

This project refactors the original index.html into a semantic, accessible version named index.semantic.html. The goal was to replace generic wrappers (div, span) with semantic HTML5 elements and improve accessibility, structure, and compliance with web standards.

Key Changes

Landmark Elements: Added header, nav, main, aside, and footer to provide clear document structure.

Headings: Replaced .title with logical heading levels (h1–h4) to create a meaningful outline.

Metadata: Converted .meta into semantic elements like <time> and <span> for author and date.

Images: Wrapped images in <figure> with optional <figcaption> for descriptive context.

Quotes: Converted .quote into <blockquote> with optional cite attribute.

Related Content: Used <section> with a heading and consistent structure (ul > li > article).

Cards: Refactored .cards and .card into a list of <article>s within a <section>.

Sidebar: Converted generic sidebar into an <aside> with subsections.

Accessibility:

Added a skip link (Skip to main content) pointing to #main.

Provided proper <label> for the search input.

Added aria-label to nav elements without visible headings.
