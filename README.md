# Country Happening

**Ian & Kellyn Are Getting Hitched**

A recreation of the original [Country Happening](http://countryhappening.squarespace.com/) wedding website, built on Squarespace in 2015 for Ian & Kellyn's wedding in West Virginia and rebuilt here as plain HTML so it can outlive the Squarespace subscription.

The name was inspired by a 1967 event hosted by architect Philip Johnson at the Glass House in Connecticut, where the Velvet Underground played and Vogue dubbed it a "Country Happening."

## Pages

- **Homepage** — Tater the dog, drawn by Kel-Kel, swapping front/back every ten seconds
- **Our Wedding** — Ceremony details and schedule
- **Itinerary** — Thursday through Sunday, as originally written
- **Getting There** — Travel and lodging information
- **Having Fun** — Things to do in West Virginia
- **RSVP** — The RSVP form, closed and preserved
- **Photos** — Ian & Kellyn through the years (73 photos)
- **Playlist** — West Virginia Wedding soundtrack
- **Road Trip** — Pit stops from NYC to WV
- **Registry** — Animal rescue organizations
- **Updates** — The two blog posts

## How it's built

No build step, no dependencies: each page is a standalone HTML file sharing `css/style.css`. The header, nav, and footer are repeated in every file, so a change to those needs to be made in all eleven pages.

Fonts come from Google Fonts: Alice (site title), EB Garamond (lead paragraphs and subheads, standing in for the original's Garamond Premier Pro), and Montserrat (everything else, standing in for Proxima Nova).

## Viewing

Open `index.html` directly, or serve the folder locally:

```bash
npx serve -l 3456 .
```

The site is published on [GitHub Pages](https://ianahall.github.io/country-happening/).
