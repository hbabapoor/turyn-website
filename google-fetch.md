# Blog Post Workflow — Google SERP Research Before Writing

Use this prompt when creating any new blog post. Run through every step before writing a word.

---

## The Prompt

Please re-write (or write) the blog post for **[PRIMARY KEYWORD]**. Use `@references/humour.md` for tone.

Before writing the blog post, do the following:

1. **Search Google** for the primary keyword
2. **Analyse the top 3 ranking pages** by fetching and reading each page
3. **Match their format** — identify whether the top pages use listicle, tutorial, guide, comparison, etc. and use the same format
4. **Match their length** — calculate the average word count of the top 3 and stay within 20% of that average
5. **Cover every topic** the top 3 all talk about
6. **Add 1–2 extra topics** they missed (use this to differentiate and outrank)
7. **Answer the main question directly at the top** in a callout box — this targets the Google featured snippet
8. **Include an FAQ section** using questions from "People Also Ask" on the Google results page

---

## What to extract from each top-3 page

- Estimated word count
- Page format (listicle / guide / comparison / tutorial / landing page)
- All H2 and H3 headings in order
- Main topics covered
- FAQ questions if present
- Featured snippet answer at top if present

---

## After writing

- Run a voice check against `references/voice.md` — delete anything that reads as AI
- Confirm humour techniques from `references/humour.md` are applied (sprinkle, don't saturate)
- Update the JSON-LD FAQPage schema to match the new FAQ questions
- Add the featured snippet callout block at the very top of the article body
- Run `npm run build` if inside a Next.js project, or validate the HTML directly

---

## Notes

- People Also Ask questions change — fetch them fresh each time, don't reuse from a previous post
- If the top 3 are all thin service pages (under 1,000 words), a comprehensive guide will outrank them — don't match thin content
- One humour technique per section maximum; none in FAQ answers or cost/timeline tables
-  create a keyword cluster that keyword cluster can either be from common keywords in the keywords that CSV file or you can just make iplease ad
d in images from pixel's and my API key is in the .env file attached
- create a html file clean and ready to upload to github and get the style of the page from custom-home-builders-north-shore.html in my seo files.
- consider all below points in the blog you make but keep the sense of hunoure in the body:
 On-Page SEO Checklist
THE COMPREHENSIVE ON-PAGE SEO CHECKLIST
On-page SEO — do these on every page.
15 categories · 80+ items · the complete on-page SEO spec for blog posts and service pages. Technical SEO (sitemaps, robots.txt, Core Web Vitals) is covered separately.

1 HEAD & METADATA — What Google indexes first

Title tag — 50–60 chars, primary keyword near the start.
Meta description — 150–160 chars, keyword + benefit + soft CTA.
Canonical URL set to prevent duplicates.
Open Graph — og:title, og:description, og:image (1200×630), og:url, og:type.
Twitter Card — summary_large_image, title, description, image.
Language attribute on <html> (e.g. lang="en").
Viewport meta tag for responsive rendering.
Favicon + apple-touch-icon.
Charset meta — <meta charset="utf-8">.


2 URL STRUCTURE — Clean, readable, keyword-forward

Short slug — under 60 chars.
Primary keyword in the slug.
Hyphens only — never underscores.
Lowercase only.
No stop words ("the", "a", "of") unless necessary.
Logical hierarchy — /services/{slug}, /blog/{slug}.


3 HEADINGS — Structure for skimmers & bots

Exactly one H1 per page, contains primary keyword.
Logical H2 + H3 hierarchy — never skip levels.
H2s use supporting keywords + questions from the cluster.
No keyword stuffing — write naturally.


4 COPY & BODY — Answer the query, fast

Primary keyword in the first 100 words.
Direct answer to the query in the first paragraph.
Length matches SERP average (within 20% of top-3).
Short paragraphs (1–4 sentences).
Readability — 8th–10th grade level.
Active voice preferred.
Bold key phrases — sparingly.
Bullets & numbered lists where appropriate.


5 FAQ SECTION — Every blog post

4–8 questions from SEMrush Questions tab + "People Also Ask".
Direct answers — 2–4 sentences each.
FAQ schema (JSON-LD) applied.


6 IMAGES — Every image is a ranking signal

Alt text describes image + keyword where natural.
Filenames — descriptive, hyphens, e.g. emergency-plumber-toronto.webp.
WebP, compressed under 200 KB.
Width/height attributes specified — prevents CLS.
Lazy loading (loading="lazy") for below-fold.
Responsive srcset where needed.
Featured/hero image for social sharing.


7 INTERNAL LINKS — Pass authority across the site

3–5 internal links per post.
Link to related blog posts & relevant service pages.
Descriptive anchor text — never "click here" or "read more".
Contextually placed in body copy.
Breadcrumbs on every page.


8 EXTERNAL LINKS — Cite authority, don't hoard it

2–3 external links to authoritative sources (.gov, .edu, major industry).
Relevant to the topic.
Open in new tab with rel="noopener".
rel="nofollow" for sponsored links.


9 SCHEMA MARKUP — JSON-LD in <head>

Article schema on blog posts.
LocalBusiness schema — most specific subtype (Plumber, Dentist…).
Service schema on service pages.
FAQ schema wherever FAQ section exists.
BreadcrumbList schema on every page.
Organization schema site-wide.
Author/Person schema for bylines.


10 E-E-A-T SIGNALS — Experience · Expertise · Authority · Trust

Author byline with name on every blog post.
Author bio with credentials (years, qualifications).
Link to author's dedicated page.
Published date displayed.
"Last updated" date when refreshed.
Real stories, numbers, opinions from the business voice file.
Cite authoritative sources.
About page with full company credentials.
Contact page — real address, phone, hours.


11 ACCESSIBILITY — A11y signals = SEO signals

Semantic HTML5 — <header>, <nav>, <main>, <article>, <footer>.
ARIA labels on interactive elements where needed.
Color contrast meets WCAG AA (4.5:1 body text).
Focus indicators visible on interactive elements.
Alt text on all images (empty alt="" for decorative).
Descriptive link text.
Skip-to-content link for keyboard users.


12 MOBILE & RESPONSIVE — Mobile-first indexing

Responsive layout (Tailwind handles this).
Touch targets minimum 48×48 px.
Body font minimum 16 px.
No horizontal scroll at any viewport.
No intrusive interstitials.


13 SOCIAL PREVIEW — Shareable card

OG image optimised — 1200×630, under 1 MB.
Twitter Card image — 1200×600.
Compelling og:description — different from meta if valuable.


14 CONVERSION ELEMENTS — Capture the lead (SERVICE PAGES ONLY)

Primary CTA above the fold.
Phone number with click-to-call tel:.
Multiple CTA placements throughout the page.
Trust signals — reviews, ratings, licences, years.
Testimonials with names (photos where possible).
Service-area coverage listed.
Business hours displayed.
Physical address with embedded map.


15 LONG-FORM CONTENT — 1500+ word posts (1500+ WORDS)

Table of contents with anchor links at the top.
Jump links for each H2.
Back-to-top button.



Point Claude Code at on-page-seo.md, then say "generate a blog post about X" — it will satisfy every item on this list automatically. That's the whole point.
80+ ITEMS · 15 CATEGORIES
