# Fethi Fırat Tülü: Personal Portfolio

Live site: https://ftulu.github.io/FFT/

A static site built with GitHub Pages and Jekyll.

## Structure

| Path | Purpose |
| --- | --- |
| `_layouts/default.html` | Shared page shell: `<head>`, meta tags, header and footer |
| `_includes/header.html` | Name and main navigation (highlights the active page) |
| `_includes/footer.html` | Social media links |
| `index.html` | About me |
| `side-projects.html` | Professional and academic projects |
| `reading.html` | Yearly reading/watching list |
| `hobbies.html` | Photo gallery |
| `assets/css/style.css` | All styles, including mobile rules |

Each page starts with front matter (`layout`, `title`, `description`). Only the page content goes in the file.

## Adding content

- **Reading list:** copy a `<section class="year">` block in `reading.html` and add `<li>` items.
- **Hobby photo:** resize to about 1000px on the long edge (≤ 250 KB), put it in `assets/images/`, and add a `<li><figure>…</figure></li>` to `hobbies.html` with `alt`, `width`, `height` and `loading="lazy"`.

## Local preview

```sh
bundle exec jekyll serve   # requires Ruby + the github-pages gem
```
