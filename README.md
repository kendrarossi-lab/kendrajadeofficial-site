# Kendra Jade (kendrajadeofficial.com)

Static website for Speak No Evil, the novel and soundtrack album by Kendra Jade, published by Krossi Culture. Both release Friday, January 15, 2027.

This folder is plain HTML and CSS. There is no build step and nothing here requires a paid plan.

## Pages

- `/` Home: the novel, the soundtrack album, music, a buy teaser, and about Kendra Jade
- `/shop/` Buy and pre-order, with coming-soon slots for ebook, paperback and album links (no placeholder store URLs)
- `/404.html` Custom not-found page

SEO is included: titles and meta descriptions, canonical URLs for https://kendrajadeofficial.com/, Open Graph and Twitter tags, a 1200 x 630 share image, favicon, JSON-LD for Book, MusicAlbum and Person (Kendra Jade, writer), sitemap.xml, robots.txt, and a CNAME file.

Store buttons stay as "coming soon" until real pre-order and pre-save links exist. The only public social link on the site is the Facebook page already used on the previous Carrd site, https://www.facebook.com/kendrajadeofficial.

## Recommended host

GitHub Pages (free, custom domain supported), the same host already used for itsgonnabeaproblem.com. The GitHub account is kendrarossi-lab, signed in with Google as kendrarossi@gmail.com. Suggested repository name: `kendrajadeofficial-site`. Enable GitHub Pages from the default branch root, set the custom domain to kendrajadeofficial.com, and keep the CNAME file in this folder. A `.nojekyll` file is included so GitHub Pages will not run Jekyll.

Until the repo is published and DNS is pointed here, kendrajadeofficial.com should keep its current forward to the Carrd site.

## DNS records for GitHub Pages (for Domains Bot, after the repo is live)

Keep Porkbun as the DNS host. Do not switch nameservers.

Root (apex) `kendrajadeofficial.com`, type A, four records:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Optional IPv6 AAAA records:

- 2606:50c0:8000::153
- 2606:50c0:8001::153
- 2606:50c0:8002::153
- 2606:50c0:8003::153

`www` CNAME: `kendrarossi-lab.github.io`

Also set the custom domain to kendrajadeofficial.com in the GitHub repo Pages settings, and enable HTTPS once the certificate is ready.

After DNS is in place, the default project URL `https://kendrarossi-lab.github.io/kendrajadeofficial-site/` should redirect to the custom domain, the same way the It's Gonna Be a Problem site does.

## Local preview

    python3 -m http.server 8080 --directory /workspace/kendrajade-site

Then visit http://127.0.0.1:8080/

## Notes

- Public credit is Kendra Jade. Imprint is Krossi Culture. Call her a writer.
- Cover art on this site is the approved photo cover already used on the Carrd page (no red thread).
- Do not add store links, YouTube, Instagram, TikTok or other socials until those accounts or listings are live and public.
- Nothing in this folder should be paid for. Carrd Pro is not required.
