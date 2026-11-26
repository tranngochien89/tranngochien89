# Personal portfolio — implementation plan

## Goal
A public, mobile-first portfolio inspired by the supplied dark navy/purple reference. GitHub profile README remains separate.

## Phase 1 — MVP
- Navigation, hero, about, expertise, grouped skills, projects, engineering approach, contact/footer.
- Responsive layout, dark/light toggle, EN/VI content, project filters, keyboard navigation and reduced-motion support.
- Use a geometric monogram instead of a fabricated portrait. No invented metrics, employment dates or credentials.
- Static HTML/CSS/JS under docs/ for zero-dependency GitHub Pages hosting. This replaces the initially proposed Next.js stack for MVP; migrate only when content complexity warrants it.
- Public projects link to their public repositories; private initiatives have descriptive summaries without internal links or customer data.
- Contact via GitHub; no fake contact form or unconfirmed email.

## Phase 2 — Content
- Obtain approved portrait, contact details, CV, work history and customer permissions.
- Add genuine screenshots, individual case studies, architecture diagrams and measured outcomes.
- Add technical articles and SEO metadata for each article.

## Phase 3 — Publishing and QA
- Settings > Pages > Deploy from a branch > main > /docs > Save.
- Verify actual deployed URL, desktop/mobile layout, keyboard navigation, contrast, language/theme toggles, links and metadata.
- Add custom domain and analytics only after approval.

## Acceptance criteria
- No external runtime dependencies, no credentials or private source exposed.
- All visible navigation and filters work; language and theme preferences persist.
- Readable at mobile widths; no fabricated claims or screenshots.
- README links to portfolio source; published URL added after verification.
