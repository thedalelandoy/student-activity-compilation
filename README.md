# Student Activity Compilation

**Dale Ysmael B. Landoy** · BS Marketing · Section ETY131 · Mapúa Malayan Colleges Laguna · A.Y. 2026–2027

A web compilation of three activities built with HTML5 and CSS3. Open `index.html` to start.

GitHub: ADD-YOUR-GITHUB-LINK

## Activities

| # | Activity | Folder | What it is |
|---|----------|--------|------------|
| 1 | Personal Portfolio | `portfolio/` | Profile, interests, skills, projects, activities, awards, timeline and contact |
| 2 | Marketplace | `marketplace/` | The Extraordinary Brand, a launch-sale skincare storefront for students and young professionals in Laguna |
| 3 | Marketing Campaign (Responsive Design) | `campaign/` | "Your website is the second email", a Casual Outbounds campaign page for agency owners who send cold email |

## Folder structure

```
student-activity-compilation/
├── index.html              compilation home page
├── css/
│   ├── brand.css           shared Casual Outbounds tokens and components
│   └── style.css           home page layout
├── images/                 profile photo and project card screenshots
├── portfolio/
│   ├── index.html
│   └── css/portfolio.css
├── marketplace/
│   ├── index.html
│   ├── css/marketplace.css
│   └── images/             product photos
└── campaign/
    ├── index.html
    ├── css/campaign.css
    └── images/             LinkedIn carousel slides used in the campaign
```

## How the requirements are met

- **Semantic HTML5:** every page uses `header`, `nav`, `main`, `section`, `article` and `footer`.
- **Separate files:** no inline styles; each page links its own stylesheet.
- **Relative paths:** all internal links, images and stylesheets use relative paths.
- **Alt text:** every meaningful image has descriptive alt text. Decorative card thumbnails use empty alt text because the card title already names the project.
- **Working navigation:** all nav links point to real section IDs or pages. "Buy Now" buttons open a pre-filled order email. Every activity links back to the compilation.
- **Responsive design:** three layouts per page (desktop, tablet below about 960px, phone below about 600–680px) using media queries, CSS Grid and Flexbox. Images use `max-width: 100%`, `height: auto` and `aspect-ratio` with `object-fit`, so they never distort. Tested at 360, 390, 768, 1024 and 1440px with no horizontal scrolling.
- **No JavaScript:** the entrance animation is pure CSS and switches off for people who prefer reduced motion.

## Design

The compilation, portfolio and campaign share the Casual Outbounds look: Inter headings with tight letter spacing, Switzer body text, a Lexend Exa wordmark, a lime-to-green wash and frosted glass cards. The marketplace keeps its own orange and yellow sale branding because it is a separate brand.
