## Design System — Non-negotiable on every page

Background: #F8F6F1
Display font: Playfair Display (loaded from Google Fonts)
Body font: system-ui
Link and accent color: match existing site

## Case Study Page Structure — All build pages follow this order

1. Results table (key outcomes at the top — what it produced, at what scale)
2. Context (why this problem needed solving)
3. Approach (what was built and how)
4. Why it matters (strategic significance for communications leadership)
5. External links (live tool, GitHub, related posts)

## GEO Metadata — Required on every page

Every page must include the following in the <head>:
- <title> tag
- <meta name="description">
- <meta property="og:title">
- <meta property="og:description">
- <meta property="og:url">
- <link rel="canonical">

## Visual Consistency Rule

All build pages at /builds/[project]/ must match the Work section visual language
exactly. A recruiter moving from the Work section to the Builds section should see
the same fonts, background, and layout structure. No exceptions.

## Output Format

All files are plain HTML. No frameworks. No external CSS files unless already part
of the existing site. Google Fonts link for Playfair Display must be included in
every new page's <head>.
