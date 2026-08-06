The **`orz-markdown` family** is the underlying document engine powering Alembic's content display, formatting, and offline portability.

While Markdown is traditionally a simple plain-text syntax used for basic formatting (like using `**bold**` or `# Heading`), basic Markdown often breaks down when handling complex academic material—such as advanced math, chemical structures, or embedded presentations—especially when exporting outside a hosted platform.

The `orz` family solves this by extending standard Markdown into a set of **self-contained, rich-formatting document tools** designed specifically for higher education and STEM courseware.

---

### The Three Core Formats in the `orz` Family

The `orz-markdown` ecosystem provides three specialized document formats tailored to different instructional needs:

1. **`orz-mdhtml` (Standard Webpages & Handouts):**
* Used for central study guides, reading assignments, casual notes, and lab worksheets.


* It compiles standard Markdown alongside embedded dynamic elements into a clean, single web document.




2. **`orz-slides` (Interactive Presentations):**
* Translates plain Markdown text directly into presentation slide decks.


* Allows instructors to draft slides in simple text without wrestling with PowerPoint formatting or layout alignment.




3. **`orz-paged` (Printable & Exportable Documents):**
* Formats course content for clean printing or high-quality PDF generation, ensuring headers, page breaks, and figures render properly.





---

### Key Capabilities for Educators

* **"Travels in One File" (Self-Contained Architecture):**
Unlike typical web pages that rely on external servers for styling, fonts, or scripts, `orz` documents package the renderer, layout styles, and content together. A single `.html` file contains everything needed to view and edit the document offline in any standard web browser.


* **Native STEM & Complex Notation Support:**
It natively renders chemical structures, mathematical equations ($\text{\LaTeX}$ / MathJax), charts, data plots, and complex tables directly from plain-text definitions without requiring external software plugins.


* **Source-Aware Copy & Paste:**
Moving heavily formatted content (like complex equations or chemical formulas) between different `orz` documents retains full structural formatting without breaking or degrading the layout.


* **AI Agent Alignment:**
The `orz` format includes specialized "agent skills" open-sourced for AI models. When Alembic's AI assistant drafts or updates course materials, these rules force the AI to format STEM notations, diagrams, and headings correctly on the first pass.



In short: **Alembic** is the overall workspace and version-control hub, while **the `orz-markdown family**` is the engine that makes the documents beautiful, interactive, and portable anywhere.