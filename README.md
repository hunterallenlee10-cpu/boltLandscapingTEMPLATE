# Copperleaf Grounds Co. (fall landscaping template)

A single-page, fall-themed website template for a landscaping and yard care business. Plain HTML, CSS and a little JavaScript, no build step. It deploys to Vercel, Netlify or GitHub Pages as a static site.

## Deploying on Vercel

Framework Preset: **Other**. Leave Root Directory, Build Command and Output Directory blank.

## Sections

Hero, service marquee, services grid (leaf removal, gutters, aeration and overseeding, fall plantings, pruning, irrigation winterization), holiday lighting, cleanup process, September to December schedule (the current month is highlighted automatically), pricing, reviews, FAQ with service area, quote form, footer. It includes light and dark mode (follows the device, with a toggle) and a mobile call bar.

## Making it yours

Everything lives in `index.html`.

- **Business details:** search for `Copperleaf`, `(610) 555-0147`, `hello@copperleafgrounds.com`, `West Chester` and `Brandywine Valley` and replace them.
- **Colors and fonts:** edit the tokens at the top of the `<style>` block (`--accent`, `--evergreen`, `--bg`, and so on). Dark mode values are in the two blocks right below.
- **Prices, reviews, towns and FAQ:** all sample content. Replace with real numbers and real customer quotes.
- **Quote form:** with no endpoint set, the form runs in demo mode and only shows the thank-you message. To receive submissions, create a form at a service like [Formspree](https://formspree.io) and paste its URL into `data-endpoint=""` on the `<form id="quote-form">` tag.
- **Photos:** in `images/`, as WebP. Swap in your own job photos with the same file names, or update the `src`/`srcset` paths.

## Photo credits

All photos are from [Pexels](https://www.pexels.com) and free to use under the [Pexels license](https://www.pexels.com/license/):
[hero](https://www.pexels.com/photo/34515430/),
[leaf blower](https://www.pexels.com/photo/9620213/),
[porch mums](https://www.pexels.com/photo/3142467/),
[pruning](https://www.pexels.com/photo/38936344/),
[holiday lights](https://www.pexels.com/photo/35371210/),
[leaves on grass](https://www.pexels.com/photo/9779101/),
[rake](https://www.pexels.com/photo/9735037/),
[leaf pile](https://www.pexels.com/photo/10559047/),
[lawn](https://www.pexels.com/photo/10258631/),
[pumpkin steps](https://www.pexels.com/photo/1486689/),
[dusk entry](https://www.pexels.com/photo/29225778/).
