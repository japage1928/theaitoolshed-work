# The Tool Shed: thetoolshed.work

Static funnel-hub website. Plain HTML + one CSS file. No build step, no framework,
no JavaScript libraries. Deploys to Netlify with zero config.

## What's here

- `index.html`: Home. Positions the site, shows the 3 products, routes people fast.
- `start-here.html`: Lead magnet page. Free Faceless Video Checklist for an email.
  Contains the Kit form placeholder (see below).
- `products/index.html`: "Which guide is right for you" comparison.
- `products/ai-remote-income-starter-kit.html`: $9.99 landing page, buy button to Payhip.
- `products/sleeper-bunk-operator-pack.html`: $99.00 landing page, buy button to Payhip.
- `products/amazon-affiliate-videos-guide.html`: $14.99 landing page, buy button to Payhip.
- `about.html`: John's story.
- `blog/index.html`: Placeholder linking to the Blogger posts until migration.
- `lead-magnet/faceless-video-checklist.html`: Print-friendly checklist. Open in a browser,
  print to PDF, and you have the lead-magnet file.
- `email/welcome-sequence.md`: 4 welcome emails with subject lines, ready to paste into Kit.
- `assets/style.css`: The one stylesheet. Mobile-first.

Checkout stays on Payhip. Every buy button links to the product's Payhip page.

## Deploy

1. Push this folder to a GitHub repo.
2. In Netlify: Add new site, import from Git, pick the repo. No build command, no
   publish directory changes needed. The site is plain files.
3. Done. Netlify gives you a `*.netlify.app` URL to preview.

## What John still needs to do himself

1. **Kit signup.** Create a free Kit (ConvertKit) account and confirm the email.
   Build a form for the checklist list, then paste the embed code into
   `start-here.html` where it says:
   `<!-- KIT FORM: paste Kit embed code here after signup -->`
   (There's a styled placeholder form there now so the design is visible. Replace it
   with the real Kit embed.)
2. **Make the checklist PDF.** Open `lead-magnet/faceless-video-checklist.html` in a
   browser, print to PDF, and upload that file as the Kit form's download / incentive email.
3. **Load the welcome sequence.** Copy the 4 emails from `email/welcome-sequence.md`
   into a Kit sequence, in order, one per day.
4. **Point the DNS.** At launch, point thetoolshed.work at Netlify (Netlify's domain
   settings walk through this: add the domain, then update DNS at the registrar).
5. **Blog migration (later).** Move posts from sleeper-income.blogspot.com into
   `/blog/` and map blog.thetoolshed.work. The placeholder page is already in place.

## Voice rules (every word on the site follows these)

Short sentences. Contractions. Plain words. No em-dashes. No income claims or hype.
Banned: fluff, unlock, game-changer, secret, skyrocket, elevate, harness, leverage,
empower, seamless, effortless, ultimate, "dive in", delve, vibrant, tapestry,
metaphorical landscape, realm, supercharge, "crush it", "buckle up",
"in today's fast-paced world", "whether you're X or Y", "look no further",
"not just X, it's Y", "say goodbye to". Specifics beat adjectives.
