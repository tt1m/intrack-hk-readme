# InTrack HK 

**A modern, full-stack internship tracking platform designed for Finance & Tech students in Hong Kong.**

InTrack HK aggregates high-quality listings from Big 4, Bulge Bracket banks, and Fintech unicorns, providing students with a unified Kanban board to organize their application process.

### Tech Stack
*   **Framework:** SvelteKit (Svelte 5 Runes)
*   **Language:** TypeScript
*   **Database:** PostgreSQL (Neon Serverless)
*   **ORM:** Drizzle ORM
*   **Styling:** Tailwind CSS + DaisyUI
*   **Auth:** Google OAuth via Arctic 

### Key Features
*   **Interactive Kanban Board:** A drag-and-drop application tracker (using `svelte-dnd-action`) with optimistic UI updates and auto-saving positioning.
*   **Advanced Filtering:** Server-side filtering by Category(Big 4/Bulge Bracket/Boutique...), Season, and Deadline types.
*   **Admin Dashboard:** A protected route for managing listings, supporting CRUD operations with reactive form handling.
*   **Custom Tracking:** Users can add "private" custom jobs to their board that don't appear in the public database.
