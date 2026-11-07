# How to add a blog post

Posts live in the `_posts` folder. Each post is one text file written in Markdown.
GitHub rebuilds the site automatically about a minute after you save.

## Option 1: on github.com (no software needed)

1. Go to https://github.com/jason-breezy/willowwindowfashions and open the `_posts` folder.
2. Click **Add file → Create new file**.
3. Name it with today's date and a short title, all lowercase with dashes:
   `2026-11-15-best-window-treatments-for-bedrooms.md`
4. Paste the template below, fill it in, then click **Commit changes**.

To add a photo: open the `images` folder, click **Add file → Upload files**, drop the photo in,
commit, then use `/images/your-photo.jpg` as the `cover` (or inside the post as `![Description](/images/your-photo.jpg)`).

## Option 2: send it to Claude

Send the blog text (Google Doc, Word file or pasted text) plus any photos, and ask for it to be posted.

## Template

```
---
title: "Your Post Title Here"
description: "One or two sentences that show up in Google results (about 150 characters)."
cover: /images/hero.jpg
cover_alt: "Short description of the cover photo"
category: Plantation Shutters
---

Opening paragraph.

## A section heading

Text for this section. Use **bold** for emphasis and [links](/consultation.html).

- Bullet point
- Another bullet point
```

## SEO tips

- Put the main search phrase in the title and first paragraph (for example "plantation shutters Toms River").
- Write a clear `description`; Google often shows it under the title.
- Link to the consultation page (`/consultation.html`) and to other posts.
- Always fill in `cover_alt` and image descriptions.
