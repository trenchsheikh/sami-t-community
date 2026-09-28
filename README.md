# Sami Tahir Community Portfolio

Portfolio site development lives in pull requests.

## Search setup after deployment

This repository does not record the site's public URL, so the HTML intentionally does not declare a canonical URL or an absolute Open Graph image URL. Once the final domain is known:

1. Point the preferred domain to the site and redirect any alternate hostnames to it.
2. Add a self-referencing `rel="canonical"` link, `og:url`, and a 1200 × 630 social image served from the public site.
3. Publish a sitemap containing the preferred homepage URL and submit it in Google Search Console. Verify the property, inspect the homepage URL, and request indexing.
4. Link to the portfolio from Sami's LinkedIn, GitHub, TikTok, Instagram, event bios, and other profiles he controls. Keep the same name and relevant bio across them.

Search ranking depends on indexing, competing pages, and signals beyond this repository; metadata alone cannot guarantee a particular position.
