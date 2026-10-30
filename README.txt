SOUQI Careers website (HTML + CSS only, no JavaScript)
Open index.html. Keep the pages, styles.css and the images folder together.

Latest changes
- Homepage: the "hiring snapshot" section (table) was removed completely, with its CSS.
- New CSS-only effects on the homepage (all at the end of styles.css, "POLISH PACK"):
  Hero:    drifting gold dust over the photo; "brilliant people." shimmers once, replays on hover;
           the search card's border catches the light once on load and while you use it;
           gold buttons get a light sweep; search box glows on focus; chips and stats lift on hover.
  Ticker:  soft gold fade at both edges (hover or the pause button stops it).
  About:   the underline under "good people." and the gold side line draw in as you scroll.
  Values:  a giant faint numeral (i / ii / iii) changes with the selected value; arrow marker on the active tab.
  Teams:   cards tilt and lift on hover; big outlined 01/02/03 numerals turn gold.
  Roles:   a gold wash sweeps across the row on hover.
  Apply:   slow drifting coloured light; the watermark text slides sideways as you scroll; gentle pulse on the button.
  Rule lines and kicker lines draw themselves as they scroll into view; footer logo tilts on hover.

Browser features used
- CSS keyframes, transitions, @property (animated angle), background-clip:text, mask-composite: all current browsers.
- animation-timeline: view() (scroll-driven draws/slides): Chrome and Edge 115+, Safari 26+. Elsewhere those parts simply show finished.
- :has() (value numerals, filters): Chrome/Edge 105+, Safari 15.4+, Firefox 121+.
- Everything that moves is switched off automatically when the visitor sets "reduce motion".

Still to add: images/group-photo.jpg (About page) and the grey "Photo:" placeholders.
