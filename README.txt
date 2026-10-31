ZippZap website – main page + Moments, Teams and Circles – version 3.2
=====================================================================

Open index.html in any browser. Every page works offline – keep the assets folder next to the four pages.

Pages
  index.html     Main page (zippzap.app) – about ZippZap as a whole only.
                 "Group love, delivered perfectly." Three short product cards (Moments, Teams, Circles)
                 with an Explore button each, "What every ZippZap includes" (six things all three share),
                 "How ZippZap works" in three steps, and a closing band with one button per product.
                 No Moments-only buttons or labels; each product page has its own download or early access.
                 Colour: neutral charcoal. Pink, blue and green appear together as the ZippZap family blend,
                 or alone on the product they belong to.
  moments.html   ZippZap Moments – families and friends. The version 2.1 home page (pink and purple,
                 15 occasion icons, plans, Google Play link and QR code).
  teams.html     ZippZap Teams – workplaces. Corporate navy and blue. 11 work occasions, company features,
                 a "For HR" section and the early access form.
  circles.html   ZippZap Circles – communities (churches and ministries, cell groups, alumni and school groups,
                 clubs and associations, family reunions). Warm green. 11 community occasions,
                 a "For leaders" section and the early access form.

  Every page has the same layout, header, footer and type (Plus Jakarta Sans).
  The product pages (Moments, Teams, Circles) carry a thin "ZippZap family" bar at the top to switch
  between them and back to the main page.

Logos – one colour version per page (same shape, name and tagline)
  Main page   logo.svg         / logo-mark.svg          the original ZippZap logo
  Moments     logo.svg         / logo-mark.svg          the original ZippZap logo
  Teams       logo-teams.svg   / logo-mark-teams.svg    corporate blue bolts, navy name
  Circles     logo-circles.svg / logo-mark-circles.svg  green bolts, deep green name
  The logo-mark files are the browser tab icons. The colour versions were made from the original logo,
  so if the original changes, the versions need making again.

assets/
  logo files listed above
  avatar.png (sample photo) · og-image.png (1200 x 630 picture shown when a link is shared)
  fonts/ (Plus Jakarta Sans) · icons/ (15 occasion icons, WebP, 256 x 256)

Early access forms (Teams and Circles)
  The forms are ready for Netlify Forms. Names: teams-early-access and circles-early-access.
  Teams asks for: name, work email, company or organisation, team size, country, and an optional note.
  Circles asks for: name, email, community or organisation, number of members, type of community,
  and an optional note.
  A hidden spam trap field is included. After sending, the form is replaced by a thank-you message.

  To switch them on in Netlify:
    1. Deploy the four pages and the assets folder (drag the folder onto Netlify, or push to the linked repo).
    2. In the Netlify site, open Forms and turn on form detection if it is off, then deploy once more.
    3. The two forms then appear under Forms. Add an email notification there so each request
       reaches the ZippZap team's inbox.
  Opened from a computer as a file (not on Netlify), the form only shows a note that nothing was sent.

Colour check for Nigeria
  - Teams uses navy and corporate blue only – the usual colour of banks and large companies – with no green,
    so it cannot be mistaken for any party or flag look.
  - Circles uses green, the national colour, never placed in green-white-red or green-white-light-blue stripes
    (the look of the main political parties), and never next to red.
  - The main page uses no red, and its dark band always carries bright colours, so it never reads as
    plain black (black or white are worn for mourning by some families).
  - Moments keeps the brand pink and purple from the ZippZap B2C Brand Guidelines v1.0.

Checked at 320, 360, 390, 768, 1024, 1440 and 1920 px on all four pages: no sideways scrolling,
buttons large enough to tap, every image and font loads, menus, forms and section highlights work, no errors.

To check before going live
  - Links /affiliates, /contact, /privacy and /terms – point them at the real pages.
  - The pages expect to live at https://zippzap.app/, /moments, /teams and /circles (canonical links and
    the link-preview picture address). Change those addresses if the site lives elsewhere.
  - All four pages share one link-preview picture (og-image.png). A blue one for Teams and a green one for
    Circles can be added later.
  - Teams and Circles say "Early access" and "plans for every team size / group size" – no prices are shown.
    Add prices when they are decided.
  - Example names (Ngozi, Pastor Ade, Tunde, Amaka …) and the sample photo can be replaced with real ones.
  - Google Play link and QR code use the app id app.zippzap.celebration – confirm it is the published listing.

Colours, type and tone follow the ZippZap B2C Brand Guidelines v1.0; Teams and Circles add their own colours.
Prepared by Manoj – RADFINKORP Solutions · 31 October 2026
