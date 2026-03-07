# Maintenance Checklist

Use this checklist once per quarter to keep the website accurate and healthy.

## Content

- Confirm current positions, roles, and dates in `index.md`.
- Review `research.md` and add new publications or awards.
- Review `industry-partnerships.md` and update project summaries and student counts.
- Check that `Last updated` dates are refreshed in all main pages.

## Links

- Verify internal links (`index.md`, `research.md`, `industry-partnerships.md`, `escritos/index.md`, `estudos/index.md`).
- Verify external links (Lattes, DBLP, publications, partner sites).
- Fix any case-sensitive path issues in markdown links.

## Assets

- Confirm all partner logos exist under `assets/img/partners/`.
- Replace broken or outdated logos with local copies.
- Ensure image `alt` text remains descriptive.

## SEO and Metadata

- Review `_config.yml` title and description for accuracy.
- Confirm `_includes/head-custom.html` still renders OG and Twitter meta tags.
- Check homepage sharing preview (title, description, image) after deploy.

## Technical

- Run local preview and review home + detail pages.
- Confirm there are no Jekyll build errors.
- Keep `Gemfile` and `Gemfile.lock` in sync when dependencies change.
