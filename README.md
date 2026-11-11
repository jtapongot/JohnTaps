# Professional Portfolio — IT Project Management

A responsive personal portfolio built with plain HTML, CSS and JavaScript. The content is based on the supplied professional resume and presents career history, responsibilities, technical skills, education and training in an engaging web format.

## Deploy free with Cloudflare Pages

1. Open Cloudflare Dashboard → **Workers & Pages**.
2. Choose **Create application** → **Pages** → **Connect to Git**.
3. Select **jtapongot/butodco**.
4. Set production branch to `main`, framework preset to `None`, leave build command blank, and set build output directory to `/`.
5. Save and deploy. Cloudflare will provide the site's `.pages.dev` address.
6. Future commits to `main` trigger deployments when the Git integration is active.

This is a static site and does not require a paid build service or application framework. Cloudflare account limits and terms apply.

## Content accuracy

The portfolio reflects the resume details supplied by the site owner. It does not invent quantified project results, client case studies, email addresses, or additional qualifications. Before public launch, add a preferred contact email and optionally a downloadable resume file.

## Files

- `index.html` — page content, career timeline, skills and credentials
- `styles.css` — responsive navy-and-gold design
- `script.js` — mobile navigation, active section and current year

## Run locally

Open `index.html` in a browser. No dependencies or build step are required.