Rana Dairy Farm website (static, no build step, one small self-hosted script for animations, no cookies or tracking; the only third-party item is the Google Maps embed on the Visit page)

Upload the contents of this folder to any static host. Entry page: index.html

Pages: index, about, milk, farm, visit, privacy, terms

Before launch:
1. Connect the custom domain at your host.
2. After the domain is live, add a sitemap.xml with the full page URLs and add the domain to robots.txt.
3. If the farm holds an FSSAI licence, add the licence number to the footer text in each page.
4. Have the privacy policy and terms reviewed by a lawyer for your situation.

Fonts (Source Serif 4, Source Sans 3, Noto Sans Devanagari) are self-hosted under the SIL Open Font License 1.1.

Animations: js/main.js handles scroll reveals, number counters, the live open/closed badge (India time, 5 AM to 8 PM) and the photo viewer on the farm page. All motion switches off for visitors who prefer reduced motion.
Photos in img/ are colour and exposure enhanced; untouched originals are kept separately in originals.zip.

Illustrations: the Home, About and Our milk pages use custom illustrations (img/illus-*.svg, drawn in the site colours). Only the Farm and Visit pages use real photographs.
