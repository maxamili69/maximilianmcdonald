# maximilianmcdonald.com

Website for Maximilian McDonald's private studio days in Mexico City.

## Swapping photos (no code needed)

The page has nine photo spots. Upload a JPG with the exact name below into the `images` folder and it appears on the site. Leave a spot empty and it simply doesn't show.

| File name | Where it appears | Best shape |
|---|---|---|
| `images/hero.jpg` | Wide photo under the headline (also the preview image when the link is shared) | Landscape, about 2:1 |
| `images/studio-1.jpg` | Next to the studio day details | Portrait, about 4:5 |
| `images/about.jpg` | Next to the About section | Portrait, about 4:5 |
| `images/gallery-1.jpg` to `gallery-4.jpg` | "From the studios" photo grid | Landscape, about 4:3 |

To upload or replace one on github.com: open the `images` folder → **Add file → Upload files** → drag in the photo (same name replaces the old one) → **Commit changes**. The site updates in a minute or two.

Keep photos under about 1 MB each (2000 px wide is plenty) so the page loads fast.

## Other settings in `index.html`

- **Application form:** paste the Formspree endpoint into `FORM_ENDPOINT` near the bottom.
- **Ad tracking:** paste the Meta Pixel and LinkedIn Insight Tag snippets where the `AD TRACKING` comment is near the top.
