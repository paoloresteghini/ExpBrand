---
name: Experiential Star
description: "Title-Card Wall: a streaming catalogue wall for once-in-a-lifetime trips."
colors:
  amber: "#e8b44c"
  amber-hover: "#f3c566"
  amber-ink: "#17120a"
  ground: "#0f1013"
  ground-2: "#17181d"
  ground-3: "#1f2127"
  ink: "#f3f0e9"
  ink-2: "#c2beb3"
  ink-3: "#96928a"
  ink-on-light: "#111111"
  line: "rgb(243 240 233 / .14)"
  slate: "#233842"
  error: "#ff9f8c"
typography:
  display:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3.3rem, min(8.4vw, 9.6vh), 6rem)"
    fontWeight: 800
    lineHeight: 0.88
    letterSpacing: "-0.015em"
    fontVariation: "'wdth' 66"
  headline:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.2rem, 5.2vw, 4.6rem)"
    fontWeight: 800
    lineHeight: 0.92
    letterSpacing: "-0.012em"
    fontVariation: "'wdth' 68"
  title:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.5rem, 2.9vw, 2.5rem)"
    fontWeight: 800
    lineHeight: 0.96
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 68"
  subtitle:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.12rem, 2.05vw, 1.7rem)"
    fontWeight: 600
    lineHeight: 1.28
    fontVariation: "'wdth' 100"
  body:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.5
    fontVariation: "'wdth' 100"
  body-long:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.08rem"
    fontWeight: 400
    lineHeight: 1.66
    fontVariation: "'wdth' 100"
  label:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.86rem"
    fontWeight: 400
    lineHeight: 1.5
    fontVariation: "'wdth' 100"
  wordmark:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.02rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.03em"
    fontVariation: "'wdth' 125"
rounded:
  xs: "2px"
  sm: "3px"
  md: "4px"
  lg: "6px"
  xl: "8px"
  full: "50%"
spacing:
  gut: "clamp(20px, 3.4vw, 48px)"
  chip-gap: "8px"
  tile-gap: "12px"
  bar: "68px"
  column-gap: "clamp(24px, 5vw, 80px)"
  chapter: "clamp(64px, 11vh, 132px)"
components:
  button-amber:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.amber-ink}"
    rounded: "{rounded.md}"
    height: "42px"
    padding: "0 16px"
  button-amber-hover:
    backgroundColor: "{colors.amber-hover}"
  button-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.ink-on-light}"
    rounded: "{rounded.md}"
    height: "42px"
    padding: "0 16px"
  button-ink-hover:
    backgroundColor: "#ffffff"
  button-line:
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    height: "42px"
    padding: "0 16px"
  button-ghost:
    textColor: "{colors.ink-2}"
    rounded: "{rounded.md}"
    height: "42px"
    padding: "0 16px"
  chip-tag:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.amber-ink}"
    rounded: "{rounded.xs}"
    padding: "2px 8px"
  chip-filter:
    textColor: "{colors.ink-2}"
    rounded: "{rounded.md}"
    height: "36px"
    padding: "0 14px"
  chip-filter-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.ink-on-light}"
  tile:
    backgroundColor: "{colors.ground-3}"
    rounded: "{rounded.md}"
    width: "clamp(128px, min(12.4vw, 18.6vh), 184px)"
  input-field:
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    height: "50px"
    padding: "0 16px"
  dialog:
    backgroundColor: "{colors.ground-2}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xl}"
  bar:
    textColor: "{colors.ink}"
    height: "{spacing.bar}"
    padding: "0 clamp(20px, 3.4vw, 48px)"
---

# Design System: Experiential Star

## Overview

**Creative North Star: "The Title-Card Wall"**

Experiential Star is laid out like a streaming catalogue at night: a deep, nearly neutral ground, rails of upright poster tiles, and one thing in focus at a time. Whatever is in focus grows, says what it is, lends its colour to the room, and is named in a bar at the bottom of the screen. Everything else dims and waits. The detail page is the same world with one poster playing: a pinned picture, the listing's own summary lines arriving as subtitles, and a scrubber bar that carries the chapters, the price and the way out.

The system is typographic before it is pictorial. A single variable family, Archivo, does all the work by changing width: condensed extra-bold capitals for anything that is a title, normal width for anything that is read. Poster photography is the only colour on the page. Where a listing has no photograph it is never left as an empty frame: it gets a typographic title card on a dark slate, sized to fill its card, and that card is treated as artwork everywhere a photograph would be.

Amber is the marquee light and it is rationed. It marks where focus is, what kind of trip this is, and the door out to the provider. Motion follows one grammar: width and position changes on an exponential ease-out, slow ambient colour drift, scroll-scrubbed pinned scenes on wide screens, and a short opening sequence on each page in which the title is cut in from a clip rather than faded.

**Key Characteristics:**
- Dark, nearly neutral ground that takes a tint from the focused poster.
- One family, two widths: condensed capitals for titles, normal width for reading.
- Upright poster tiles in rails; the focused tile widens to landscape and reveals its facts.
- A fixed bottom bar on every page that names what is in focus and holds the actions.
- Typographic title cards in a slate family stand in for missing photographs.
- Amber only on the focus ring, the tag chip and the way out.
- Flat surfaces separated by hairlines; shadow appears with focus and with overlays.

## Colors

A dark cinema room: three steps of near-black ground, three steps of warm off-white ink, one amber, and whatever colour the posters bring.

### Primary
- **Marquee Amber** (`amber`, #e8b44c): the focus ring (2px outline, 3px offset) on every focusable element and on the focused tile; the tag chip; the filled button that leaves for the provider (View experience in the title-card dialog and the detail scrubber, Join free and continue in the member gate). Also the text selection, the input caret, the skip link and the outline of a Top ten numeral while its tile is focused, all of which are focus states. Hover is `amber-hover`. Text on amber is always `amber-ink`.

### Neutral
- **Ground** (`ground`): the page. A fixed layer behind the content paints two soft radial washes of the ambient colour over it (top right at 82% mix, bottom left at 22%), plus a 3% noise grain.
- **Ground 2** (`ground-2`): dialogs, sheets and the suggestion panel.
- **Ground 3** (`ground-3`): tile and image placeholders, the action column of the member gate.
- **Ink** (`ink`): titles, primary text, the search underline, filled states of sliders, progress segments and selected chips.
- **Ink 2** (`ink-2`): reading text, secondary facts, resting controls.
- **Ink 3** (`ink-3`): captions, counts, placeholders, inactive index entries.
- **Ink on light** (`ink-on-light`): text on ink-filled surfaces (the ink button, a selected filter chip, the trailer play disc).
- **Line** (`line`): every hairline border and divider, ink at 14% alpha. Hover raises a border to `ink-2`.
- **Slate** (`slate`): the representative title-card colour. Each listing carries its own dark colour in the data: cool slates and violets for listings without a photograph, a dark tone drawn from the photograph for the rest. That one value paints the title card, the thumbnail fallback and the ambient wash.
- **Error** (`error`): form error message text and the invalid-field border.

### Named Rules
**The Marquee Rule.** Amber appears in three places only: where focus is, the tag chip, and the filled action that sends the visitor to the provider. No other button, link, heading or decoration is amber. Selection and state elsewhere are shown by inverting to ink.

**The Borrowed Light Rule.** The interface owns no hue but amber. The room's colour comes from the focused listing: its colour is written to the ambient property and the ground drifts to it over 1.1s, linearly. Posters that are not in focus are held back (saturation 68%, brightness 80%) and return to full colour on focus or hover.

**The One Slate Rule.** A listing without a photograph is a title card, not a placeholder. The card is a 165 degree gradient of the listing's own dark colour, from slightly lifted to mixed toward black, with the title in ink. No icons, no pattern, no stock stand-in.

## Typography

**Display Font:** Archivo variable, width 62 to 125, weight 100 to 900 (with Helvetica Neue, Arial, sans-serif)
**Body Font:** the same family at width 100

**Character:** One grotesque played like a film title sequence. Squeezed and heavy it reads as a poster; at normal width it reads as plain, calm text. The contrast between the two widths is the whole typographic system.

### Hierarchy
- **Display** (800, width 66, clamp(3.3rem, min(8.4vw, 9.6vh), 6rem), line-height 0.88, uppercase): the page title. One per page. On the detail page it steps down for long names (width 62) and, on a title card, is sized by a per-title factor in container units so the name fills the frame.
- **Headline** (800, width 68, clamp(2.2rem, 5.2vw, 4.6rem), line-height 0.92, uppercase, balanced): section titles, dialog titles, the mood list entries and the finder's spoken result (width 70).
- **Title** (800, width 62 to 78, clamp(1.5rem, 2.9vw, 2.5rem), line-height 0.92 to 0.96, uppercase): tile titles, write-up subheads, the writers' credits, the up-next link. Width narrows as the name gets longer (78 for short, 68 for medium, 62 for long) instead of the size shrinking first.
- **Subtitle** (600, width 100, clamp(1.12rem, 2.05vw, 1.7rem), line-height 1.28, centred, balanced, max 36ch): the summary beats over the pinned picture, with a soft dark text shadow for legibility on photography.
- **Body** (400, width 100, 1rem, line-height 1.5): everything read in passing; `ink-2`, max 46 to 60ch. Long-form write-ups use 1.08rem at line-height 1.66 with a 68ch measure, and the first paragraph steps up to clamp(1.18rem, 1.7vw, 1.4rem) in `ink`.
- **Label** (400 to 600, width 100, 0.86rem to 0.94rem, sentence case): field labels, facts, counts, button text (0.94rem at 500, 600 on filled buttons). Rail headings are 600 at 1rem, sentence case, not capitals.
- **Wordmark** (800, width 125, 1.02rem, letter-spacing 0.03em, uppercase): the site name in the nav and footer, the only expanded setting.

### Named Rules
**The Width Is The Voice Rule.** Hierarchy comes from Archivo's width axis, not from a second typeface. Titles are condensed (62 to 78), extra-bold, uppercase and tightly led. Reading text, labels and controls are width 100 and sentence case. The wordmark alone is expanded.

**The Fit The Card Rule.** A title never truncates on its own card. Narrow the width first, then scale by the card (container units driven by the longest word and total length), and let it wrap balanced.

**The Tabular Figures Rule.** Prices, counts and view figures use tabular numerals wherever they sit in a row or update in place.

## Layout

Full-bleed, no centred container. A single fluid gutter (`gut`) is the only side margin, and rails deliberately run off the right edge. Two fixed bars frame every page at 68px each: a transparent nav at the top that turns to blurred ground with a hairline once the page scrolls, and a bottom bar that never leaves. Body content reserves the bottom bar's height.

Tiles are upright posters at a fixed 1:1.44 ratio, 128 to 184px wide in rails, 12px apart, bottom aligned. Section splits are asymmetric two-column grids (roughly 1 to 1.1, 0.9 to 1.25, 0.8 to 1.5) with a fluid gap (`column-gap`); they never resolve to equal card grids. Chapters on the detail page are separated by generous fluid top padding (`chapter`) rather than rules or boxes.

Wide screens pin scenes to the viewport and scrub them with scroll: the numbered Top ten reel travels sideways, the mood switcher steps through its list, and the detail page's opening picture holds while the subtitles change. At 900px and below, columns stack, pinned homepage scenes become ordinary horizontal scrollers, button labels collapse to icons, and the detail scrubber's chapter segments move to a thin strip on the top edge of the bar. On touch devices (no hover) tiles do not widen; every tile shows its title instead and rails snap. With reduced motion the detail reel unpins and all animation and transition durations collapse.

### Named Rules
**The One Focus Rule.** There is exactly one focused listing on the homepage at any moment, moved by pointer, keyboard or scroll. The focused tile, its lifted rail, the dimmed other rails (42% opacity, 72% on touch), the ambient tint and the dock all read from that single focus. Never give two things the focused treatment at once.

**The Bar Never Leaves Rule.** The bottom bar is always on screen and always holds the current subject and its actions: the now-showing dock on the homepage, the chapter scrubber with price on the detail page.

## Elevation & Depth

Flat by default. Depth is tonal (the three ground steps), hairline (`line`) and dimming. Shadow is reserved for the thing in focus and for layers that float above the page. Fixed bars are not shadowed: they are ground at 82 to 90% alpha with a backdrop blur (14 to 16px) and a hairline on the inner edge. Dialog backdrops are near-black at 72% with a 6px blur. Photographs under text get a bottom-up black scrim rather than a panel.

### Shadow Vocabulary
- **Focus lift** (`box-shadow: 0 24px 46px -14px rgb(0 0 0 / .8)`): the focused tile only.
- **Popover** (`box-shadow: 0 24px 60px -12px rgb(0 0 0 / .7)`): the search suggestion panel.
- **Overlay** (`box-shadow: 0 40px 120px -20px #000`): the title-card dialog, command palette and member gate.
- **Thumb** (`box-shadow: 0 2px 10px rgb(0 0 0 / .5)`): the slider thumb.

### Named Rules
**The Lift On Focus Rule.** No surface at rest casts a shadow. A tile earns one when it takes focus; a panel earns one when it floats over the page.

## Shapes

Tight, squared corners throughout, like printed cards. The default radius is 4px (tiles, buttons, inputs, filter chips). Small inset pieces go tighter: 2px for the tag chip, thumbnails and progress tracks, 3px for badges, tags and the focus ring. Larger frames go slightly softer: 6px for the suggestion panel, the trailer frame and the title-card frame, 8px for dialogs. True circles are used only for the slider thumb, the trailer play disc and map points; the list count is the only pill.

Borders are always 1px hairlines in `line`. The exceptions are deliberate: the search field is a single 2px ink underline with no box, and the Top ten numerals are drawn as 2px outlined figures with no fill. Posters carry a 1px inner hairline (ink at 10%) so dark images keep an edge against the ground. Progress is always a 3 to 4px rounded bar filled left to right in ink (slider track, chapter segments, beat marks). Icons are 18px line icons on a 24 unit grid, 1.8 stroke, round caps and joins.

## Components

### Buttons
Compact, quiet and squared; only one of them is ever lit.
- **Shape:** 42px tall, 16px side padding, gently squared (4px), icon and label 9px apart, label at 0.94rem weight 500. Form-row buttons grow to 50 to 52px to match their input.
- **Amber (the way out):** amber fill, `amber-ink` text, weight 600, always with the outbound arrow icon. Used for View experience and for Join free and continue. Hover lightens the fill. At most one per view.
- **Ink:** ink fill with dark text, weight 600, hover to white. The primary action that stays on site (Start my list, Join free, Sign in and open it).
- **Line:** 1px hairline border, ink text. Hover raises the border to `ink-2` and adds a 6% ink wash. Secondary actions: Add to list, My list, Full story, Continue without joining, and View experience in the homepage dock.
- **Ghost:** no border, `ink-2` text, hover to ink with a 7% ink wash. Nav tools.
- **Icon button:** 40px square, 4px corners, same hover wash. Close and rail arrows.
- **Text link:** `ink-2`, underlined in `line` with a 0.2em offset; hover turns text to ink and the underline to full strength.
- **Focus:** the global ring, 2px amber at 3px offset.

### Chips
- **Tag chip:** amber fill, `amber-ink` text, 0.78rem weight 600, 2px corners, 2px by 8px padding. One per listing, naming its first category. Not interactive.
- **Filter chip:** 36px tall, hairline border, `ink-2` text, 4px corners; may carry a small tabular count in `ink-3`. Hover raises border and text. Selected inverts to ink fill with dark text, weight 600.
- **Outline tag:** hairline border, 3px corners, 0.82rem, `ink-2`. The full tag list inside the title-card dialog.
- **Members badge:** small dark scrim label with a lock icon, top left of a member-only tile.

### Tiles and Title Cards
The unit of the whole system.
- **Poster tile:** upright 1:1.44, 4px corners, clipped, inner hairline. Photograph held back at rest, full colour on focus or hover with a slow 4% zoom.
- **Focused tile:** amber ring, focus-lift shadow, raised 6px, and on hover-capable screens widened to 2.42 times its width over 0.5s on the system ease while neighbours slide aside. A bottom scrim fades in with the title, tag chip, country and price.
- **Title card:** for listings without a photograph. Slate gradient, title in condensed capitals sized to the card, country and price beneath in `ink-2`. When focused it widens like any tile and keeps its own title rather than gaining a scrim. On the detail page it becomes the whole opening frame, outlined by a single hairline with 6px corners.
- **Numbered tile (Top ten):** a tile overlapped on its left by an outlined numeral (weight 900, width 62, up to 24rem); the outline turns amber while that tile is focused.
- **Article card:** landscape (1:0.62), hairline border, fixed dark slate gradient, headline in condensed capitals fitted to the card, a quiet Read link at the foot. Hover lifts it 6px and raises the border.

### Inputs / Fields
- **Search line:** no box. A 62px row with a search icon, large input text and a keyboard hint, closed by a 2px ink underline that doubles in weight while the field is focused. Caret is amber. Suggestions open in a `ground-2` panel beneath, grouped, with poster thumbnails and the matched letters set in bold ink.
- **Text field:** 50px tall, hairline border, 4px corners, faint ink fill (7%) on the page or `ground` inside a dialog. Focus shows the amber ring flush to the edge. Invalid fields take the error border and a message in `error` beneath.
- **Range slider:** a 4px track filled in ink up to the value over a 20% ink remainder, with a 22px round ink thumb.

### Navigation
- **Top nav:** fixed, 68px, transparent over the opening; after 24px of scroll it takes ground at 82% with a 14px blur and a bottom hairline. Expanded wordmark at left, section links in `ink-2` (hover to ink), tools at right: search with keyboard hint, membership, My list with a count pill. Below 900px the links and hints hide and labels collapse to icons.
- **Now-showing dock (homepage):** fixed bottom bar, ground at 90% with a 16px blur and a top hairline. A small poster thumbnail, the focused listing's name (600) and its country and price (`ink-3`), then Add to list and View experience as line buttons. Its text swaps with a short rise each time focus moves.
- **Scrubber (detail page):** the same bar. Left: one segment per chapter, each a 3px progress bar that fills in ink as that chapter is read, with its label beneath; the current chapter's label is ink at 600. Right: the price in condensed capitals, Add to list, and the amber View experience. Clicking a segment, clicking a beat mark and the arrow keys all move along the same track.
- **Section index (detail write-up):** a sticky list of the write-up's headings in `ink-3`; the current one is ink at 600.

### Dialogs
- **Title-card dialog:** two columns, artwork left and facts right, 8px corners, overlay shadow, rises 24px into place. Holds the amber View experience, Full story and Add to list.
- **Member gate:** two columns, the case for joining on `ground-2` and the action on `ground-3`. The email field, then the amber Join free and continue when the visitor is on the way out (ink when they are not), a text link to switch to sign in, and Continue without joining as a full-width line button pinned to the foot, absent on member-only listings.
- **Sheet:** a full-height panel from the right edge with a hairline on its left (My list, Photo credits), sliding in 40px.
- **Command palette:** the search line and suggestion list in a dialog set 12vh from the top.

### Openings
Each page plays one short entrance, built from the same shared keyframes. Homepage: the headline is cut in from a clip, the search line draws left to right, chips rise in sequence, the first rail's tiles are dealt in from the right 60ms apart, then focus opens and the dock slides up. Detail page: the picture opens from a letterbox while brightening, the title is cut in, facts and subtitle rise, the scrubber slides up. Everything runs on the system ease, cubic-bezier(.16, 1, .3, 1), inside about two seconds, and collapses under reduced motion.

## Do's and Don'ts

### Do:
- **Do** keep amber to the focus ring, the tag chip and the filled action that leaves for the provider, with at most one amber button in view.
- **Do** set every title in Archivo condensed capitals (width 62 to 78, weight 800, line-height under 1) and every sentence, label and control at width 100 in sentence case.
- **Do** give a listing without a photograph a title card in its own slate colour, fitted to the frame, everywhere a photograph would appear.
- **Do** route every new focusable listing through the single global focus so the ring, the ambient tint and the bottom bar stay in agreement.
- **Do** keep the bottom bar on screen on every page, holding the current subject and its actions.
- **Do** show selection and progress by filling or inverting to ink (selected chips, slider, chapter segments, beat marks).
- **Do** use 1px hairlines in `line` and the three ground steps to separate things; add a shadow only for the focused tile and for floating layers.
- **Do** move things with the system ease, cubic-bezier(.16, 1, .3, 1), over 0.5s for focus and layout, 0.2s for hover colour, and let the ambient tint drift linearly over 1.1s.
- **Do** unpin scroll scenes at 900px and below and honour reduced motion.

### Don't:
- **Don't** put amber on a button that stays on site, on headings, links, icons or decoration.
- **Don't** introduce a second interface hue. Colour belongs to the posters and the ambient tint they cast.
- **Don't** bring in a second typeface, or set body text, labels or buttons in condensed capitals.
- **Don't** leave an empty or grey picture frame, or substitute an icon or pattern, where a photograph is missing.
- **Don't** round corners past 8px or use pill buttons; the count pill and true circles are the only fully round shapes.
- **Don't** give resting surfaces a shadow, and don't box sections in bordered panels.
- **Don't** truncate a title on its own card; narrow the width, then fit it to the card.
- **Don't** show two focused tiles, or let the bottom bar name something other than what is in focus.
