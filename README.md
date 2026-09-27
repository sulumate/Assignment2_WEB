# Assignment 2 — Advanced CSS

**Student:** Aizharykova Sulukhan · **Group:** SE-2529

A personal website with a dark espresso background, cream-and-pink cards, and a few pixel illustrations. The light cards keep dark text for readability. It is built with HTML and CSS only. All site images are stored locally; no framework, JavaScript or build step is needed. The home page uses a 3:4 pixel portrait.

## Pages and assignment tasks

| Page | Task | What it demonstrates |
| --- | --- | --- |
| `index.html` | Navigation | A Flexbox header with a logo and links to separate pages |
| `flexbox.html` | Card row | Three cards with images, text, buttons, equal heights, gaps and hover effects |
| `grid.html` | Grid areas | A header, left sidebar, right main area and full-width footer using named grid areas |
| `grid.html` | Image gallery | Nine local images in a responsive CSS Grid with captions that stay visible |
| `portfolio.html` | Combined layout | Flexbox header and project cards; Grid for projects on the left and profile information on the right |

## Open locally

Open `index.html` in a browser and use the navigation to visit every page. The site also works without an internet connection, except that the gallery's biography links open external sources.

## Publish with GitHub Pages

1. Upload the **contents of this folder** to the root of a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Select **Deploy from a branch**, then choose `main` and `/ (root)`.
4. Save and wait for the published URL. Test every navigation link on the published site.

The source images of Sulukhan were used only to create the two pixel illustrations included in `assets/`. The nine gallery images are interpretive pixel illustrations, not historical photographs.

## Key CSS to explain at the defense

- `.site-header`, `.nav-list` and `.card-row` use `display: flex` for alignment and consistent spacing.
- `.story-card` and `.story-card-body` use column Flexbox; the link stays at the bottom with `margin-top: auto`.
- `.profile-grid` uses `grid-template-areas` to place `header`, `sidebar`, `main` and `footer`.
- `.pioneer-grid` uses equal-width Grid columns and changes to two or one column on smaller screens.
- `.portfolio-layout` puts projects left and profile information right, then stacks them on mobile.

## Biographical sources for the gallery

- [Ada Lovelace — Computer History Museum](https://www.computerhistory.org/babbage/adalovelace)
- [Marie Curie — Nobel Prize](https://www.nobelprize.org/prizes/physics/1903/marie-curie/facts/)
- [Grace Hopper — Computer History Museum](https://computerhistory.org/profile/grace-murray-hopper/)
- [Hedy Lamarr — National Inventors Hall of Fame](https://www.invent.org/inductees/hedy-lamarr)
- [Katherine Johnson — NASA](https://science.nasa.gov/people/katherine-johnson/)
- [Rosalind Franklin — King's College London](https://www.kcl.ac.uk/the-story-behind-photograph-51)
- [Chien-Shiung Wu — American Physical Society](https://www.aps.org/apsnews/2022/09/lee-yang-parity)
- [Radia Perlman — Internet Hall of Fame](https://www.internethalloffame.org/inductee/radia-perlman/)
- [Maryam Mirzakhani — International Mathematical Union](https://www.mathunion.org/imu-awards/fields-medal/fields-medals-2014)
