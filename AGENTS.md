# Portfolio update instructions

## Scope

- Keep the site focused on character rigging and Autodesk Maya.
- Do not invent projects, credits, employment, experience, skills, or results.
- Do not add email addresses, social links, or contact details to the website.
- Use only images the user provides for portfolio entries. Do not add generated or stock artwork as project work.
- Preserve the current dark, restrained visual style and responsive layout.

## Project map

- `index.html` is the portfolio landing page and project-card grid.
- The first project card links to `project-01.html`.
- Project 01 images belong in `assets/project-01/`.
- For a new project, create `project-XX.html`, an `assets/project-XX/` folder, and a matching card in `index.html`. Keep project numbers unique and zero-padded.

## When the user attaches an image

1. Treat an image as a portfolio update only when the user indicates it belongs in the portfolio. If it may be a reference image, or the target project is unclear, ask before adding it.
2. Choose the project from the user's explicit project number or name. “First project” means Project 01. If multiple projects could match, ask which one.
3. Use the title and date supplied by the user. If no date is supplied, use the date the image was provided in the `Asia/Seoul` timezone. If the title cannot be described accurately from the user's context, ask instead of inventing details.
4. Assign the next unused step number for that project, starting at `01`. Do not reuse or renumber existing step IDs.
5. Save the original image under the project's asset folder. Use a lowercase filename such as `step01-title-2026-11-20.jpg`, preserving the original file extension when possible.
6. Add the image to that project's timeline with the visible caption exactly in this format: `STEP XX: Title - YYYY-MM-DD`.
7. Keep timeline entries ordered by date, oldest first. If a newly supplied image has an earlier date, place it by date but preserve all existing step numbers.
8. After the first image is added, remove the empty-state message and update the displayed step count. Write concise, factual alt text based only on information the user supplied or what is plainly visible.
9. If the user attaches several images for one project, add one timeline entry per image and number them in the order the user specifies; otherwise use their dates to organize the entries chronologically.

## Project cards and timeline pages

- Keep empty project cards as placeholders until the user provides real project material.
- Make a project's card open its matching detail page.
- When a real first image is provided, it may replace the card's empty preview; do not change the title or add claims without user context.
- Keep the timeline caption format consistent across all project pages: `STEP XX: Title - YYYY-MM-DD`.

## Publishing

- Do not claim a change is live until the repository push succeeds and the published page can be confirmed.
- The GitHub Pages source for this user site is the `main` branch at the repository root.
