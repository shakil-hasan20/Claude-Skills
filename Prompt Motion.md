---
name: prompt-motion
description: Creates and improves motion design prompts for animations, transitions, visual effects, and UI interactions. Use when creating or refining motion design prompts.
---

# Prompt Motion

Prompt: Character Motion

Create a Pixar-inspired 3D animated comedy short called "The Package." A curious young man receives a mysterious cardboard package at his front door. There is no sender, no return address, and no explanation. He brings it inside. Suddenly, the package starts making strange tapping sounds. Close-ups, suspenseful music, dramatic lighting. The noises grow louder. Neighbors become concerned. Rumors spread. Crowds gather outside. News reporters arrive. Emergency vehicles appear. Experts investigate. The situation escalates into a city-wide spectacle. Fast-paced comedic montage, cinematic camera movements, exaggerated reactions. Unable to ignore the mystery, the man finally decides to open the package. Everyone watches in complete silence. Inside is another smaller box. He opens it. Another box. And another. And another. The sequence becomes increasingly absurd as dozens of boxes are revealed one inside another. The crowd becomes more invested with every opening. Suspense reaches maximum tension. Finally, the tiniest box contains a folded note. Close-up. The note reads: "Congratulations. You just got UNBOXED." Confused, the man looks around. Then notices a hidden camera. His best friend steps out laughing. The crowd erupts in laughter. The man facepalms before eventually laughing too. Final cinematic wide shot of friends and neighbors laughing together as the tower of empty boxes surrounds them. On-screen text: "Sometimes the biggest surprises are the ones that make you laugh the most." Pixar-style 3D animation, mystery-comedy tone, expressive acting, cinematic suspense, smooth transitions, playful storytelling, dramatic build-up with humorous payoff, high-end animated short film quality, vibrant colors, 16:9.


Prompt: 3D Motion

A high-quality 3D stylized character figurine in a 'Toon' aesthetic. The character is a young male with detailed hair, wearing stylish oversized streetwear including a textured hoodie with bold typography and baggy cargo pants. The clothing features realistic fabric physics and intricate details like stitching and distressed textures. The character has expressive, large eyes and wears trendy accessories like glasses and a beanie. Background is a clean, solid pastel color with large 3D bold typography reading '3D SHAPE'. Hyper-realistic textures, cinematic studio lighting, soft shadows, 8K resolution, octane render, vivid colors, and a shallow depth of field for a professional toy-photography look.


Prompt: 3D Character Motion

Create a 4-second ultra-cute vertical animated character video. A tiny fluffy purple puppy-like creature with soft fur, a round face, big glossy expressive eyes, a small black nose, short floppy ears, and adorable baby proportions. The style is polished soft 3D animation, very cute, smooth fur, pastel purple background, soft studio lighting. The character walks forward slowly with natural body bounce and soft paw movement, first looking slightly away with an innocent expression. Then it turns its head and upper body toward the camera, gives a surprised but cheeky look, and raises one hand to show one middle finger clearly. It then turns forward again for a brief beat as if continuing to walk, then quickly looks back at the camera with a more mischievous expression and raises both hands, showing two middle fingers clearly at the same time. End on the double gesture for a brief moment so it is readable. Focus on smooth body plasticity, head turn, shoulder turn, eye movement, hand gesture clarity, and cute facial expression. The eyes must be large, shiny, and very expressive. The fur must look soft and detailed. The motion must be funny, cute, and playful, not aggressive. No text on screen. No captions. No overlays. Visual style: ultra-cute polished 3D character animation, soft pastel lighting, clean background, meme-ready, adorable but sassy. No realism, no horror, no ugly face, no distorted eyes, no extra fingers, no extra limbs, no blurry motion, no low-detail fur, no dark background, no aggressive tone, no human body proportions.


Text animation 01:

# Tidewell — "Tides in Motion" scroll story: full recreation prompt

Build a single-file, four-part scroll-story landing page for a fictional coastal motion studio called **Tidewell**. It is one `index.html` with inline CSS and vanilla JavaScript (no libraries, no build step). The page is a long scroll: a light hero whose headline assembles itself out of tiny pixel icons, a pinned stage where a fan of painterly coastal art cards scatters, piles up and re-fans into a rotating wheel under a "From shore to product" headline, a dawn-sky panel that grows from the centre with a floating cream instant camera that finally zooms into its own lens, and a black manifesto section that scrolls one huge line of text sideways while pastel stickers and 3D trinkets pop in. Everything below must be reproduced exactly: every string, colour, size, asset URL, timing, easing and scroll range.

---

## 1. Assets (use these exact URLs; do not re-host)

Every image is loaded through the Higgsfield image proxy: `https://images.higgs.ai/?default=1&output=webp&url=<URL-encoded source>&w=<width>&q=85`. In the table, "source" is the URL to encode into that template. All sources share the prefix `https://d8j0ntlcm91z4.cloudfront.net/user_38xzZboKViGWJOttwIXH07lWA1P/`.

| Name | Source file (append to prefix) | Proxy width | What it is |
|---|---|---|---|
| Grid A | `hf_20261118_061436_77e1a13d-60a0-4746-bf7b-53b2365609f5.png` | 900 | 2×2 sheet, 1744×2336, four 3:4 card paintings: top-left lighthouse on dark rocks at a peach sunset; top-right peach scallop shell on lavender clouds; bottom-left blue harbour with white sailboats and a pastel town; bottom-right top-down beach, white surf on peach sand |
| Grid B | `hf_20261118_061435_8a1828bc-a149-44ea-80fd-c4c33eef7407.png` | 900 | 2×2 sheet: TL white lighthouse on rocks in a pink dawn sea; TR dark teal wave crashing with white foam; BL teal barrel wave with a tiny surfer silhouette; BR lavender-pink dawn sky over a flat sea |
| Grid C | `hf_20261118_061433_df51e37b-d8b8-40b1-9830-01ea6c20c83d.png` | 900 (300 for the chip) | 2×2 sheet: TL peach scallop shell on pale sand; TR white sailboat on a lavender sea at dawn; BL deep slate-blue open sea; BR pale blue shallows with foam lines on sand |
| Sky plate | `hf_20261118_061434_a222c9d2-715b-44b7-873f-0548d1624211.png` | 2400 | 2688×1152 dawn sky, blue-grey to peach clouds, no objects |
| Sky video | `hf_20261118_065029_a6ae2ebb-cd79-41fd-ae60-6b66fdda04ee.mp4` (use the CloudFront URL directly, not the proxy) | — | Kling 3.0 clip, 1280×720, 24 fps, 5.04 s, silent: the same sky as a fast cloud time-lapse that loops back to its first frame |
| Camera | `hf_20261118_061547_10365665-40d3-4390-944f-7bcb10dc6d4a.png` | 1400 | 2048×2048 transparent PNG, a cream retro instant camera seen 3/4 from the front (no branding) |
| Sticker sheet | `hf_20261118_061547_979f8673-f904-4102-90a0-6458bce33bc8.png` | 1200 (plane), 700 (stickers) | 2048×2048 transparent PNG with four 3D objects: TL pink-white spiral conch shell, TR pearly peach sphere, BL glossy peach-pink capsule, BR folded white paper plane |

**Sprite cropping (no local slicing).** Show part of a sheet by setting, for a crop box `[x0,y0,x1,y1]` in 0–1 image fractions with `dx=x1-x0`, `dy=y1-y0`: `background-size: (100/dx)% (100/dy)%` and `background-position: (x0/(1-dx))*100% (y0/(1-dy))*100%` (use 0% if dx or dy is 1). Crop boxes: paper plane `[.594,.613,.891,.816]`, conch shell `[.109,.121,.430,.422]`, pearl `[.625,.152,.863,.395]`, capsule `[.094,.656,.418,.793]`, camera `[.148,.141,.879,.809]` (camera element aspect ratio 1.094). A card shows one quadrant of a grid: `background-size:200% 200%`, position `0%/100%` horizontally for left/right cell and `0%/100%` vertically for top/bottom cell.

**Font:** Inter (variable, weights 100–900), latin subset, self-hosted woff2 from `https://fonts.gstatic.com/s/inter/v20/UcC73FwrK3iLTeHuS_nVMrMxCp50SjIa1ZL7.woff2`, `font-display:swap`. Fallback stack: `system-ui, -apple-system, "Segoe UI", sans-serif`. Body weight 500.

---

## 2. Colour tokens

| Token | Hex | Use |
|---|---|---|
| bg | `#F1ECEA` | page canvas (warm shell-pink off-white) |
| ink | `#1F2430` | headlines, nav current link, dark buttons, pixel-icon outlines |
| muted | `#938B90` | grey accent words, nav links |
| dark | `#12141B` | manifesto background, blackout |
| sky1 / sky2 | `#C0C9D9` / `#EFCEBE` | dawn sky palette |
| peach | `#DDAD95` | stickers, sun icon |
| lavender | `#B0AEC6` | stickers |
| harbour blue | `#7DA3BB` | pixel-icon fill |
| sand | `#EBC9AE` | sticker |
| rose | `#BF9FA5` | — |
| slate | `#4C6165` | — |
| ice | `#BAD9E6` | stickers |
| sub-line grey | `#5B5A62` | process sub-line |
| sky grey words | `#8D8893` | grey words on the sky |
| manifesto grey words | `#6E7180` | grey words on black |
| CTA hover | `#2E3546` | dark button hover |

---

## 3. Scaling system

All sizes are computed in JS on load and on resize, and written as CSS custom properties on `:root`.

- `W = innerWidth`, `H = innerHeight`. **Mobile layout** when `W < 820 && W < H*1.1` (portrait phones and portrait tablets); landscape phones use the desktop layout.
- `--u = min(W/1440, H/800)` px (design unit, used for the plane size).
- `--n` = nav/edge unit: mobile `min(1, W/560)`, desktop `clamp(W/1440, 0.62, 1.25)`.
- `--hfs` hero headline size: mobile `min(W*.12, H*.09)`, desktop `min(W*.074, H*.135)` (≈106 px at 1440×900).
- `--ic` pixel icon size = `hfs*.62`.
- `--pfs` process headline: mobile `min(W*.085, 40)`, desktop `min(W*.0335, H*.062)`.
- `--sfs` sky words: mobile `min(W*.09, 44)`, desktop `min(W*.042, H*.078)`.
- `--mfs` manifesto line: mobile `min(W*.11, H*.075)`, desktop `min(W*.05, H*.1)`.
- `--camw` camera width: mobile `min(W*.62, H*.34)`, desktop `min(W*.19, H*.36)`.
- Card width `cw` (px, set as `--cw` unitless on the cards container): mobile `min(W*.30, H*.2)`, desktop `min(W/1440, H/780)*218`. Card height = `cw*1.32`, radius `cw*.075`, centred on its transform point (margin −0.66cw / −0.5cw). Card shadow `0 cw*.03 cw*.09 rgba(31,36,48,.16)` plus `inset 0 0 0 1px rgba(255,255,255,.35)`.

---

## 4. Page structure (DOM in order)

1. **Fixed nav** (z 50, height `86n`, side padding `40n`, flex space-between, pointer-events only on children):
   - Logo (46n square SVG, viewBox 48, currentColor = ink): a filled circle at (24,12.5) r 8.5 (a "head"), a filled wave band path `M6 27c6-5 13-5 18 0s12 5 18 0v6c-6 5-13 5-18 0S12 28 6 33z`, and a stroked wave `M10 39c5-3.6 10-3.6 14 0s9 3.6 14 0` (stroke 4.2, round caps). Link to top, aria-label "Tidewell home".
   - Centre links, 15n, weight 400, tracking −0.005em, gap 28n, colour muted, current/hover ink: **Home**, **Our Team**, **Cases**, **Features**, **Pricing**, **Contact**. Hidden below 820 px. Home→top, Our Team/Cases→process, Features/Pricing→product, Contact→manifesto (anchor clicks jump to 20% / 74% of the story scroll, or to the manifesto top).
   - Dark pill button **View Collections** + 16n arrow icon (path `M3 8h10M9 4l4 4-4 4`, stroke 1.6): height 42n, padding 0 16n 0 20n, radius 12n, bg ink, text bg colour, 15n weight 500.
   - When scrolled past 98.5% of the story or into the manifesto, the body gets `dark-nav`: logo white, links `#8C8F9A`, current link white, button white with ink text.
2. **`<section id="story">`**, height **1600vh**, position relative. Contains:
   - **Hero** (`<header>`, absolute top 0, full width, 100vh, z 9, pointer-events none). It is its own section: it scrolls away 1:1 with the page while the stage below stays pinned. Inside:
     - Headline holder at top 41%, height 0, font `--hfs`, weight 560, tracking −0.035em, line-height 1, ink. Role heading level 1, aria-label "Tides in Motion". It contains the word row (centred, each character its own inline-block span, start hidden) and an icon layer (7 absolutely positioned pixel icons).
     - Paper plane element (62u square, sprite of the plane crop), hidden until it flies.
   - **Pinned stage** (`position:sticky; top:0; height:100vh/100svh; overflow:hidden; bg`), containing in z order:
     - Process block (z 4), top 20% (17% on mobile), centred, 16 px side padding: two-line headline at `--pfs`, weight 500, line-height 1.12, tracking −0.03em: line 1 "**From** shore [chip] **to** product", line 2 "built **through** real process" (bold words above = muted grey; the rest ink). Each word is an inline-block. The chip is 1.05em × 0.92em, radius .16em, vertical-align −.12em, margin 0 .14em, shadow `0 .06em .18em rgba(31,36,48,.18)`, showing Grid C's top-right cell (sailboat at dawn). Sub-line "Turning concepts into working digital products." at `pfs*.27`, weight 400, `#5B5A62`, margin-top `pfs*.42`. Dark pill **View All Collections** + arrow: height `pfs*.64`, font `pfs*.25`, padding 0 `.28pfs` 0 `.32pfs`, radius `.2pfs`, margin-top `.38pfs`.
     - Cards layer (z 2): 12 card divs.
     - Sky panel (z 6), full stage, initially hidden: the sky plate (inset −4%, cover), the sky video over it (left/top −4%, 108% size, object-fit cover, fades in to opacity .78 over 1.2 s once playing, playbackRate **0.6**, muted, looped, playsinline), the camera (centred at 50%/51%, width `--camw`, drop shadow `0 camw*.12 camw*.08 rgba(60,52,70,.22)`), top-left words "**Not just** visuals" at left 40n/top 104n, and bottom-right words "**Real** products **that** run" at right 40n/bottom 46n (mobile: 16 px insets, top 84 px / bottom 28 px). Sky words: `--sfs`, ink, grey words `#8D8893`, tracking −0.03em, each word an inline-block.
     - Blackout layer (z 8), colour dark, opacity 0.
3. **`<section id="manifesto">`**, height **950vh**, bg dark, with a sticky 100vh stage holding the horizontal track (absolute, left 0, top 50%, flex row, items centred, gap `mfs*.32`, nowrap, font `--mfs`, tracking −0.03em, white).

---

## 5. The 12 cards

Card art (index → grid cell): 0 B-BR (lavender dawn sea), 1 A-TR (shell on lavender), 2 A-BL (harbour), 3 A-BR (beach surf), 4 B-TL (pink lighthouse), 5 B-TR (crashing wave), 6 C-TR (sailboat), 7 C-TL (shell on sand), 8 B-BL (surfer barrel), 9 A-TL (sunset lighthouse), 10 C-BL (slate sea), 11 C-BR (shallows). Cards 0–5 are the hero fan; 6–11 join later.

Each card pose is `[x, y, rotation°, scale, opacity]` (x/y = card centre in stage px). Poses:

- **Card spacing (fan and wheel):** neighbouring cards always keep a visible gap. The angular step between cards is `step(R) = 2·asin(1.05·cw / (2R))`, so the chord between two card centres is 1.05 × the card width (a small, even gap of about 5% of a card).
- **Fan (hero, cards 0–5).** Desktop: `R = 1250*W/1440`, angle `θ = (i − 2.5) × step(R)`, centre `cx = W*.55`, `cy = H*.86 + R`; x = `cx + R*sinθ − W*.02`, y = `cy − R*cosθ`, rotation θ. Mobile: `R = W*1.35`, θ = `(i − 2.5) × step(R)`, `cx = W*.5`, `cy = H*.86 + R`, y gets `+cw*.2`. Cards 6–11 wait hidden at `(W*.5, H*1.4)`.
- **Scatter** (fractions of W, H, rotation): desktop 0 `(.08,.46,−20)`, 1 `(.20,.86,−12)`, 2 `(.80,.84,14)`, 3 `(.38,1.04,−8)`, 4 `(.92,.42,16)`, 5 `(.62,1.04,9)`; cards 6–11 stay invisible. Mobile cards 0–5: `(.06,.60,−20)`, `(.45,.66,12)`, `(.94,.60,16)`, `(.22,.93,−14)`, `(.72,.96,9)`, `(.5,1.3,0)`. On screens shorter than 500 px, scatter y values below .1 are lifted by .08. No card may cover the nav or the process text.
- **Pile:** x = `W*.5 + ((i%3)−1)*cw*.08`, y = `H*.62 + (((i*7)%5)−2)*cw*.04`, rotation `±(4 + i*1.3)°` (sign alternates by index), opacity 1.
- **Wheel/arc:** 12 slots; `slot = ((i + rot) mod 12) − 5.5`; angle = slot × step(R) (the same gap rule as the fan); `R = 900*W/1440` desktop or `W*1.2` mobile; centre `(W*.5, H*.82 + R)` desktop or `(W*.5, H*.76 + R)` mobile; x = `cx + R*sin`, y = `cy − R*cos`, rotation = angle; visible only when |angle| < 62°. `rot` = −3 × (wheel progress) so the cards travel right-to-left along the arc.

**Per-card inertia:** after computing the target pose for the current scroll, each card's displayed pose moves toward it by `k = 1 − (1 − w)^(dt/16.67)` per frame with `w = .055 + (i%4)*.008` (so cards arrive one after another, softly). At scroll progress ≈ 0 the pose is applied directly (no lag during the load animation).

---

## 6. Load sequence (time-based, t in seconds from page load)

| t | What happens |
|---|---|
| 0.15–0.35 | Logo fades in (ease-out cubic) |
| 0.20 + i×0.03 → 0.42 + i×0.03 | Each nav link fades in and rises 6 px, left to right |
| 0.23–0.42 | "View Collections" button wipes open from its right edge (clip-path inset from the left, round 12n), ease-out cubic |
| 0.33–1.27 | Paper plane flies a Catmull-Rom path through (t, x% of W, y% of H): (.33, −3, 73), (.45, 4, 71), (.60, 13, 65), (.70, 22, 55), (.80, 31, 44), (.87, 32.5, 47.5), (.93, 26, 48), (1.00, 21.5, 45), (1.07, 22.5, 51.5), (1.15, 27, 52) — a climb, a small loop back — and lands at 1.27 s on the first icon slot of the headline row. Its rotation follows the direction of travel + 18°. 1.27–1.33: shrinks to 0.6 and fades out as the first pixel icon (a plane) takes its place |
| 0.53, 0.60, 0.63, 0.70, 0.80, 0.86 | Hero cards rise from below the screen (start y = H + cw*1.2, start rotation +8°) in the order card 5, 2, 0, 1, 3, 4; each takes 0.7 s with a soft back-out (overshoot 1.15) |
| 1.27 + (0.03 + j×0.07) | Pixel icons 2–7 pop in to the right of the plane icon (scale back-out over 0.32 s, fade 0.12 s). The row of 7 icons is centred on the headline line |
| 1.9 → ≈5.2 | **Icon-to-letter morph.** Every 0.22 s one more character of "Tides in Motion" appears (15 characters incl. spaces). The leftmost icon to be consumed squashes into a dark stroke (scaleY 1→.16, scaleX 1→1.25, rotate 0→−28° over the first 45% of the step, then rotates a further −62° and fades; brightness 1→0 so it reads as an ink stroke). The new letter wipes in left-to-right with clip-path over 32–90% of its step. The number of icons left is `ceil(7 × lettersLeft / 13)`. Letters and remaining icons stay as one centred group, sliding with a cubic-bezier(.25,.75,.2,1) glide every step, so the finished word ends perfectly centred. When the word completes, all icons are gone |

**Pixel icons** (9×9 SVGs, `shape-rendering:crispEdges`, each cell a 1.02 rect). Palette: k ink `#1F2430`, b harbour `#7DA3BB`, w white, p peach `#DDAD95`. Order: paper plane, scallop shell, sailboat, lighthouse, fish, wave, sun. Rows (top to bottom, `.` = empty):
- plane: `........k` `......kkb` `....kkwkb` `..kkwwkb.` `kkwwwkbb.` `..kkkbb..` `....kb...` `....k....` `.........`
- shell: `...kkk...` `..kbwbk..` `.kbwbwbk.` `kbwbwbwbk` `kwbwbwbwk` `.kbwbwbk.` `..kbbbk..` `...kkk...` `.........`
- boat: `....k....` `....kb...` `....kbb..` `...wkbbb.` `..wwkbbb.` `....k....` `kkkkkkkkk` `.kpppppk.` `..kkkkk..`
- lighthouse: `...kkk...` `..kbbbk..` `...kwk...` `...kbk...` `...kwk...` `...kbk...` `..kwwwk..` `..kbbbk..` `.kkkkkkk.`
- fish: `.........` `...kkk..k` `..kbbbkkk` `.kbwbbbbk` `kbbbbbkkk` `.kbbbbk.k` `..kkkk...` `.........` `.........`
- wave: `.........` `...kkk...` `..kbbbk..` `.kbwwbbk.` `kbw..kbbk` `kb....kbk` `bbbbbbbbb` `kkkkkkkkk` `.........`
- sun: `....p....` `.p..k..p.` `...kpk...` `..kpppk..` `pkpppppkp` `..kpppk..` `...kpk...` `.p..k..p.` `....p....`

Icon gap = 0.2 × icon size; gap between the last letter and the first icon = 1.6 × that.

---

## 7. Scroll choreography

**Smooth scrolling (desktop, fine pointer only):** wheel events are intercepted; the target scroll moves by `deltaY × 0.75` (×32 for line-mode deltas) and the page jumps there natively, while a smoothed value `sy` chases it with `sy += (ty − sy) × (1 − (1 − .06)^(dt/16.67))` (frame-rate independent, ≈0.8 s glide). If no wheel event for 250 ms, the target re-syncs to the real scroll position (keyboard, scrollbar, anchors). Touch devices use native scrolling.

Story progress `p = clamp((sy − story.top) / (story.height − H), 0, 1)`. Phases (eInOut = cubic in-out, eGlide = cubic-bezier(.25,.75,.2,1)):

| p range | Motion |
|---|---|
| 0 → ~0.06 | The hero section scrolls away 1:1. The headline fades from opacity 1 to 0 as its top moves from `navHeight + 1.9×fontSize` down to `navHeight + 0.55×fontSize`, so it disappears before it reaches the nav |
| .004 → .085 | Cards blend from fan to scatter (eInOut) |
| .05 → .075 | The process block fades in (opacity follows p). Below .05 it is hidden and its word reveal resets, so scrolling back up never overlaps the hero headline |
| > .078 | Process words reveal once (time-based): word i fades in, rises from .35em and un-blurs from 6 px over 0.55 s, starting at i×0.11 s (ease-out cubic). Sub-line 0.7–1.2 s, button 0.85–1.35 s (fade + 8 px rise) |
| .21 → .31 | All cards gather into the centre pile (eInOut); cards 8–11 fade in during this |
| .31 → .41 | Pile fans out into the wheel along the bottom (eGlide) |
| .41 → .57 | The wheel turns 3 slots, cards travelling right-to-left (eInOut) |
| .57 → .62 | Hold: the wheel rests |
| .62 → .74 | **Gated:** the sky panel may only start once the wheel has finished turning AND every card has settled (each card within 3 px / 1° of its target pose). Until then its progress target is 0; once allowed, its displayed progress chases the scroll value with the same frame-rate-independent glide (weight .09 per frame). So on a fast scroll the camera and sky wait for the card marquee to finish, then catch up smoothly. The sky panel grows from a small rounded window (desktop 17% × 20% of the stage, centred 12% above the middle; mobile 42% × 16%, 6% above) to full bleed using clip-path inset with corner radius 14 px → 0 (eInOut). The plate and video scale 1.18 → 1. The camera scales .5 → 1 with the panel. The video plays only while the panel is visible |
| when the panel is full | Sky words reveal (time-based): "Not", "just", "visuals" at 0, .12, .24 s; "Real", "products", "that", "run" at .45, .57, .69, .81 s; each 0.6 s fade + .3em rise + 6 px blur-out |
| .74 → .88 | Camera yaws from −10° to +10° (perspective 900 px) and bobs ±6n px on a 1.6 rad/s sine |
| .88 → .97 | Camera zooms into its lens: `q = ((p − .88)/.09)^1.6`, multiplied by the sky panel's own progress gate (0 until the panel is ≥ 90% grown, 1 when full), scale `1 + q²×28`, transform-origin 54% 31% (the lens). Blackout fades in over q .45 → .85. The nav switches to its dark style at p > .985 |

**Manifesto** (progress `mp` over its 950vh): the track translates from x = `W*.06` (mobile `W*.08`) to `−(trackWidth − W*.9)`, vertically centred. An item reveals once when its left edge passes `W*.86` (mobile `.92`), and only after the section is within 20% of the viewport:
- Words: each character starts at opacity 0, translateY .55em, rotate 14° (origin bottom-left) and drops into place over 0.5 s with a 35 ms stagger (ease-out cubic).
- Stickers and objects: 120 ms delay, then scale 0 → 1 with a back-out (1.15) over 0.5 s, rotating from −14° to their resting angle.

Track contents, in order:
1. Intro block (font .72em, two rows, gap .26em): row 1 "**Designing** motion", row 2 "that moves **people.**" (bold = grey `#6E7180`). Three small labels (font .24em of the line, padding .3em .6em, radius .16em, ink text, shadow `0 .12em .3em rgba(0,0,0,.35)`): "motion studio" `#EFCEBE` at top −.95em/left 0, rotated −6°; "since the tide turned" `#EBC9AE` at top −1.1em/left 3.4em, −4°; "coast to coast" `#BAD9E6` at bottom −1em/left .6em, +4°.
2. Conch shell object, 1.25em wide, −12°.
3. "**Crafting**".
4. A vertical stack: label "tidal" `#DDAD95` (−8°, with a small ink dot at its top-right corner) over the small label "and immersive" `#B0AEC6` (+6°).
5. "**animation**" "experiences."
6. Sparkle (0.34em four-point star, path `M10 0c.8 5.6 3.6 8.6 10 10-6.4 1.4-9.2 4.4-10 10-.8-5.6-3.6-8.6-10-10 6.4-1.4 9.2-4.4 10-10z`, colour `#F4E3D3`), pearl .8em.
7. "The" "ocean" "**–**" "**is**" "**a**".
8. Label "tidal" `#EFCEBE` (−8°), conch 1.05em (+10°), pearl .5em, sparkle, label "coastal" `#B0AEC6` (+3°).
9. "**and**" "**a**", label "drift" `#BAD9E6` (−10°), capsule 1.05em (−8°).
10. "atelier" "that" "brings" "brands," "stories," "**and**" "experiences" "**to**" "**life**" "**through**" "art," "design," "**and**" "technology." then a 30vw spacer.

Big labels: font .42em of the line, padding .28em .62em .3em, radius .16em. (Bold words in this list are grey `#6E7180`; the rest white.)

---

## 8. Mobile and reduced motion

- Below the mobile breakpoint the nav links hide (logo + button remain), and the alternative fan, scatter, wheel, sky-window and font sizes above apply. Check at 375×812, 320×568, 812×375, 568×320 and 768×1024: no horizontal scroll, nothing cut off, every control visible.
- `prefers-reduced-motion: reduce`: the intro jumps to its end state (full headline, cards in the fan), the sky video is not loaded, card inertia and wheel smoothing are off, and the story/manifesto sections drop their tall heights (sticky stages become normal blocks).

---

## 9. Acceptance checklist

- The hero headline builds from 7 coastal pixel icons into "Tides in Motion" and is fully formed at about 5.2 s; the paper plane's flight ends exactly on the first icon.
- The hero scrolls away as its own section; its headline is gone before it reaches the nav, and scrolling back up never shows it on top of the process text.
- Cards: fan → scatter (clear of nav and text) → pile → wheel → wheel turns right-to-left, all gliding softly with staggered inertia.
- The sky grows from a rounded centre window; the Kling clouds drift at 0.6× under a soft veil; the camera yaws, then zooms into its lens to black.
- The manifesto letters drop in and the stickers pop with a spring as the line scrolls sideways.
- All assets load from the URLs above, and only Inter is used.



Text animation 02:

# Prompt: Leon Vasari, VHS filmography shelf hero

Give me the superdetailed exact prompt to recreate this page exactly as it is, including the correct asset URL, all elements, animations, and fonts. This is that prompt.

## What it is

Build a single-screen **filmography hero** for a fictional film director, Leon Vasari. Use plain HTML, CSS and vanilla JavaScript in one file, with no framework, no build step and no libraries.

The page is a warm off-white sheet of paper. Across its middle runs a long, endless shelf of worn VHS tape boxes standing side by side, spine out. One tape, the active film, is pulled out of the shelf and **physically turned in 3D** so its illustrated front cover faces you. It is tilted a few degrees, lifted slightly and pushed towards the viewer.

- **Changing film:** click any spine, the arrows, a decade tab, scroll, drag or use the keyboard. The shelf slides, the open tape turns back into a spine, and the new one turns out to show its cover.
- **Caption:** the film's title, romanised Japanese title, kanji title and year sit under the shelf and slide up through a mask whenever the film changes.
- **Cursor:** a large custom ring cursor follows the mouse. It shrinks over spines and becomes a filled cobalt "OPEN / 開く" disc over the active cover.
- **Opening a film:** click the cover, the play ring or press Enter. A sheet of paper grows out of the cover, rotating from the cover's tilt to straight, until it fills the screen. It becomes a detail page whose poster bleeds in like ink blots spreading on paper, while each line of text rises out of its own mask.

Everything is driven by one `requestAnimationFrame` loop plus the Web Animations API, with no CSS keyframes. There is no opacity fade anywhere; every reveal is a mask slide, a clip or a scale.

## Media: every asset URL

All 24 images come from **four Higgsfield GPT Image 2.5 generation sheets** with transparent backgrounds. Each sheet is loaded through the Higgsfield image proxy as WebP, and the alpha is kept. The art is fictional, unbranded VHS art, with no real studios or logos.

Never use separate image files. Each spine and cover is a **rectangle cut out of one of these sheets** with CSS background cropping, using the exact pixel boxes below.

### Sheets

| Sheet id | Size (px) | Contents | URL |
|---|---|---|---|
| covers | 1744 × 2336 | all 12 covers in a 4 × 3 grid | https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261029_010644_837e04ca-2418-45c1-b8e0-0233265c4cd5.png&w=1744&q=85 |
| spines | 2688 × 1152 | 12 spines in one row (9 are used: all except river, observer and storm) | https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261029_010738_a3e47ead-18f2-4974-9468-06d16a25edc5.png&w=2688&q=85 |
| fix | 1520 × 2688 | re-drawn spines; the first one, RIVER OF SALT, is used | https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261029_010831_3ebb874b-93dc-433e-87ed-6299aba720f0.png&w=1520&q=85 |
| fix2 | 1520 × 2688 | re-drawn spines THE OBSERVER and LIGHT IN THE STORM | https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261029_092020_f96bc094-db7b-46de-9298-074a24e0a3b8.png&w=1520&q=85 |

### Crop boxes

The boxes are in sheet pixels, as `x, y, w, h`.

- **Spines:** a tall, narrow worn cardboard box side, about 1:6. It has a small illustration at the top, the title running vertically in a condensed serif, then "VASARI" and a boxed "VHS" badge at the bottom.
- **Covers:** about 1:1.95. Each is the front of the same box: "A LEON VASARI FILM" at the top, a big condensed serif title, a duotone screen-print illustration in ink black, cobalt, vermilion and cream, and a "VHS" badge bottom right.

| Film id | Spine sheet | Spine box | Cover sheet | Cover box |
|---|---|---|---|---|
| valley | spines | 266, 31, 189, 1089 | covers | 497, 72, 344, 659 |
| bluehour | spines | 492, 31, 189, 1089 | covers | 914, 72, 342, 659 |
| river | fix | 197, 54, 324, 2566 | covers | 1332, 72, 344, 659 |
| summer | spines | 937, 31, 188, 1089 | covers | 74, 813, 344, 676 |
| green | spines | 1157, 31, 185, 1090 | covers | 497, 815, 344, 674 |
| noon | spines | 44, 32, 184, 1088 | covers | 74, 72, 347, 659 |
| observer | fix2 | 371, 15, 349, 2655 | covers | 915, 815, 342, 675 |
| birds | spines | 1573, 31, 183, 1089 | covers | 1331, 815, 345, 675 |
| storm | fix2 | 808, 15, 347, 2656 | covers | 74, 1571, 345, 681 |
| tide | spines | 2012, 31, 188, 1089 | covers | 496, 1577, 343, 678 |
| war | spines | 2236, 31, 189, 1089 | covers | 913, 1579, 343, 676 |
| door | spines | 2462, 31, 188, 1089 | covers | 1331, 1579, 344, 677 |

### How the images are used

Put the two tables into JS as `SHEET[id] = [url, W, H]` and `CROP['spine-<id>' | 'cover-<id>'] = [sheet, x, y, w, h]`.

- **Spines and covers** are drawn as a cropped background on the box faces. For a box `x, y, w, h` on a sheet of size `W × H`, set:
  - `background-image: url(sheet)`
  - `background-size: (W/w·100)% (H/h·100)%`
  - `background-position: (x/(W−w)·100)% (y/(H−h)·100)%`

  The crop is stretched to fill the face exactly, so the spine is exactly `--ws` wide and the cover exactly `--d` wide.
- **The detail poster** is an SVG `<image>` of the cover's sheet, inside a `<g clip-path>` with a 474 × 900 rect, so the ink mask can still be applied.
  - Set the image's `href` to the sheet URL, with `x = −x·474/w`, `y = −y·900/h`, `width = W·474/w` and `height = H·900/h` (`preserveAspectRatio="none"`).
  - Only the cover's box then shows, stretched to 474 × 900.
- **Preloading:** preload the four sheet URLs as `Image()` objects on start, so the first turn never shows an empty face.

## Fonts

Self-host all five. The single-file version embeds them as base64 WOFF2 data URLs.

| Family | Weight / style | Use | Source |
|---|---|---|---|
| Newsreader (variable, optical size 6–72) | 400 regular, plus 400 italic | Caption title, detail title, synopsis, italic credit line | https://fonts.googleapis.com/css2?family=Newsreader:opsz,wght@6..72,400 and `ital,opsz,wght@1,6..72,400` (Latin subset) |
| Inter Tight (variable) | 500 and 600 | Every small uppercase label, tab, button, year, meta line | https://fonts.googleapis.com/css2?family=Inter+Tight:wght@500;600 (Latin subset) |
| Noto Sans JP | 500 | Every Japanese character in labels and titles; second in the sans stack | https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@500&text=… subset to exactly the kana and kanji used on the page (about 14 KB) |
| Noto Serif SC | 700 | The logo characters 莱昂·瓦萨里 only | https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@700&text=莱昂·瓦萨里 (about 2 KB) |

- **Sans stack:** `"Inter Tight", "Noto Sans JP", system-ui, sans-serif`.
- **Serif stack:** `"Newsreader", Georgia, serif`.
- **Japanese subset:** the subset string must contain every kana and kanji in the film data and UI. That is 戻る, すべて, 閉じる, 開く, 監督作品, 映画を見る, 年, 〜, the twelve kanji titles, and the right single quote. Romanised titles are written without macrons (SHOGO, SENSO), so the Latin subset is enough.

## Palette and tokens

| Token | Value | Used for |
|---|---|---|
| `--paper` | `#EDEBE6` | Page background |
| `--sheet` | `#F4F2ED` | Detail sheet background (slightly lighter paper) |
| `--ink` | `#141414` | All text, borders, cursor ring |
| `--muted` | `#6D6A63` | Detail meta line and italic credit |
| `--cobalt` | `#1F3FB0` | Logo, tab indicator, subtitles, play ring, OPEN cursor, Watch button |
| `--rule` | `rgba(20,20,20,.9)` | 1px borders of every boxed label |
| `--ease` | `cubic-bezier(.2,.8,.2,1)` | Every CSS transition and text slide |
| `--H` | `min(46vh, 31vw)` on desktop, `min(60vw, 40svh)` on mobile | Height of every tape; all geometry scales from it |

### Paper grain

A fixed, full-screen layer (`z-index 40`, `pointer-events none`) sits above the shelf and caption, under the detail sheet.
- **Pattern:** a 220 × 220 inline SVG tile, made from `feTurbulence` fractalNoise (baseFrequency `.85`, 3 octaves, stitchTiles) through an `feColorMatrix` that maps it to warm grey `rgb(.45,.42,.38)` at alpha `.22`.
- **Blend:** `mix-blend-mode: multiply` at `opacity .55`. The whole page reads as printed paper and the tapes pick up the grain too.

### Global behaviour
- `body` hides overflow and uses `user-select: none` and antialiased smoothing.
- On fine pointers (`@media (pointer:fine)`) the native cursor is hidden on html, body, buttons and links.

## Label system

- **`.lbl`:** Inter Tight 600, 10.5px, line height 1, letter-spacing `.09em`, uppercase.
- **`.box`:** inline-flex, 21px tall, 0 8px padding, 1px `--rule` border. It looks like the small boxed tags in printed film catalogues.

## Layout, top to bottom (desktop)

Everything is `position: fixed` and positioned from the centre of the viewport using `--H`, so the composition is identical at any desktop size.

### 1. Top bar

- **Bar:** 84px tall, 32px side padding, a 3-column grid `1fr auto 1fr`, items centred vertically.
- **Left:** a boxed label link "BACK / 戻る", aligned to the start, ink colour, no underline.
- **Centre, the logo:** a two-line stack centred with a 5px gap, all cobalt.
  - Line 1: "莱昂·瓦萨里" in Noto Serif SC 700, 22px, letter-spacing `.04em`.
  - Line 2: "LEON VASARI" in Inter Tight 600, 9px, letter-spacing `.34em`, with matching left padding so it is optically centred.
- **Right:** "CAREER 1958年〜1989年" as a `.lbl`, aligned to the end.

### 2. Decade tabs

- **Position:** centred horizontally, top at `50% − H/2 − 86px`, so they float just above the shelf.
- **Buttons:** five boxed `.lbl` buttons in a row, each 23px tall with 0 11px padding and a 1px border. `margin-left: −1px` makes neighbours share one border. Labels: "ALL / すべて" (written "All / すべて" and uppercased by the label style), "1950s", "1960s", "1970s", "1980s". Labels never wrap.
- **Indicator:** a cobalt block, absolutely positioned behind the buttons. It is the full 23px tall, and its `width` and `transform: translateX()` are set to the active tab's `offsetWidth` and `offsetLeft`. Both transition over `.6s var(--ease)`, so the cobalt block slides and stretches from decade to decade.
- **Active tab:** its text turns white via a `.45s` colour transition.
- **Which tab is active:** always the decade of the active film. For example, Noon in Ashes (1971) highlights "1970s". "ALL" is never highlighted.

### 3. The shelf (3D stage)

- **Section:** full width; top at `50% − H/2 − 40px`; height `H + 80px`.
- **Perspective:** `perspective: 2200px`, `perspective-origin: 50% 50%`, `touch-action: pan-y`.
- **Stage:** a zero-size `.stage` at `left 50%; top 50%` with `transform-style: preserve-3d`, holding every tape.
- **Tape element:** `.tape` is a zero-size box at the stage origin, with `transform-style: preserve-3d`, `will-change: transform` and two faces.

**Box dimensions**, measured from the real `--H` at load and on resize. Measure it by inserting an off-screen probe element with `height: var(--H)` and reading its height.

| Name | Value | Meaning |
|---|---|---|
| H | resolved `--H` in px | Tape height |
| ws | `H × 142 / 840` (≈ 0.169 H) | Spine width (front face) |
| d | `H × 474 / 900` (≈ 0.527 H) | Cover width = box depth |
| gap | `H × 0.03` | Gap between spines |

`ws` and `d` are written onto the stage as the CSS variables `--ws` and `--d`.

**Faces.** Each face is absolutely positioned, `H` tall, top at `−H/2`, with `backface-visibility: hidden` and a 2px radius.
- **Spine face `.sp`:** width `--ws`, left `−ws/2`, `transform: translateZ(d/2)`. This is the front of the cuboid.
- **Cover face `.cv`:** width `--d`, left `−d/2`, `transform: rotateY(90deg) translateZ(ws/2)`. This is the right-hand side of the cuboid. It also has `box-shadow: 0 30px 60px −28px rgba(20,16,10,.55)` so the pulled-out tape casts a soft shadow on the paper.
- **Shading:** each face has an `::after` overlay of solid black whose opacity comes from a `--shade` variable. As the box turns, the spine darkens to 55 % and the cover brightens from 50 % dark to fully lit. It reads as light falling across a turning object.

**Endless shelf.**
- **Copies:** render the 12 films **three times**, 36 tapes with virtual index `v = copy × 12 + i`. Wrapping then always happens far off-screen.
- **Relative position:** each tape's position comes from its relative index `r` to the current scroll value `s`. Take `(v − s)` modulo 36 into the range −18 … +18.
- **Culling:** tapes whose computed x is more than `W/2 + 1.5 d` from centre get `visibility: hidden` and are skipped.

**Horizontal placement.**
- **Formula:** the centre of a tape at relative index `r` sits at `x = F(r) = r·(ws + gap) + (d − ws + 1.6·gap)·B(r)`.
- **The smooth step `B(r)`:** for `|r| < 1` it is `(r + sin(πr)/π) / 2`, otherwise `±0.5`.
- **Effect:** spines step by spine width plus gap, and the open cover pushes neighbours apart by exactly half its extra width on each side. Because `B` is continuous, a fractional `s` slides everything smoothly with no jumps.

**Turning a tape.**

| Quantity | Formula |
|---|---|
| Openness `o` | `smoothstep(max(0, 1 − |r|))`, where smoothstep(x) = x²(3 − 2x). 1 for the active tape, 0 for spines; in between while the shelf moves, so tapes the shelf passes half-open and close |
| rotateY | `−90°·o + tiltY·o` (the box turns left until its right side, the cover, faces front) |
| rotateX | `tiltX·o` |
| rotateZ | `−4.5°·o` (the pulled-out cover leans slightly anticlockwise, like the reference) |
| translateZ | `o · 0.2 H` (pulled towards the viewer, so it looks bigger than the spines) |
| translateY | `−o · 0.025 H − lift · 0.045 H` (raised slightly; hovered spines rise more) |
| Transform order | `translate3d(x, y, z) rotateZ() rotateX() rotateY()` |
| z-index | `round(100 − |r|·4)`, so nearer tapes stack on top |
| `--shade` | Spine face: `o × .55`. Cover face: `(1 − o) × .5` |

**Hover lift.**
- **When it lifts:** hovering any tape that is not the active one (`|r| > .5`) sets that tape's lift target to 1. It eases towards the target at `1 − e^(−12·dt)` per frame, so the spine rises by 4.5 % of H, like a finger pulling it halfway out.
- **Tracking:** hover is tracked with `pointerenter` / `pointerleave` on each tape.

**Tilt towards the cursor.**
- **When the cursor is "on the cover":** within `0.55 d` horizontally of screen centre, within `0.55 H` vertically of the shelf centre, not in the detail view, and the shelf almost settled (`|T − s| < .3`).
- **On the cover:** `tiltY` targets `(mx − W/2) / (0.55 d) × 9°` and `tiltX` targets `−(my − cy) / (H/2) × 6°`.
- **Elsewhere:** `tiltY` drifts to `(mx − W/2)/W × 5°` and `tiltX` to 0.
- **Smoothing:** both ease at `1 − e^(−7·dt)`. The open cover leans gently towards the mouse like a card held in the hand.

### 4. Play ring

- **Shape:** a fixed 42px circle with a 1px cobalt border, cobalt colour, `rgba(237,235,230,.75)` fill, and a 12px solid play triangle nudged 2px right.
- **Position:** centred on the active cover's lower-left corner, at `left = W/2 − 0.5 d − 6px` and `top = shelf centre + 0.36 H`.
- **Scale:** `smoothstep(max(0, 1 − |T − s|·3))`. It pops in once the shelf settles and shrinks to 0 while the shelf moves or the detail is open.
- **Action:** clicking it opens the detail.

### 5. Caption

- **Position:** a centred stack, top at `50% + H/2 + 30px`, 9px gap, `pointer-events none`.
- **Masked lines:** each line is an `overflow: hidden` mask, `width: min(92vw, 760px)`, centred text.
  - **Title:** Newsreader 400, 31px, line height 1.12, letter-spacing −.01em (e.g. "Noon in Ashes").
  - **Subtitle:** a `.lbl` in cobalt at weight 500: romaji, " / ", kanji (e.g. "HAI NO SHOGO / 灰の正午").
  - **Year:** Inter Tight 500, 11px, letter-spacing .08em (e.g. "1971").
- **Swap animation, whenever the active film changes:**
  - A new span is appended. Its siblings are absolutely positioned over the first, so the two overlap inside the mask.
  - The new span slides from `translateY(dir × 105%)` to 0.
  - Every older span that is not already leaving slides from its current transform to `translateY(−dir × 105%)` and is removed when done.
  - Timing: 650ms, `cubic-bezier(.2,.8,.2,1)`, `fill: both`.
  - `dir` is the direction of travel: +1 going right, so text comes up from below; −1 going left, so it comes down from above.
  - When you flip quickly through several films, each intermediate title passes through the mask in turn.
  - Calling setActive also updates the decade indicator.

### 6. Arrows

- **Buttons:** two 44px buttons at the caption title's height (`top: 50% + H/2 + 40px`), 20px in from each side.
- **Icons:** 18 × 10 SVG arrows, a 1.2px stroke in currentColor. Left: a chevron `M5 1 L1 5 L5 9` plus a shaft to x 17. Right: the mirror image.
- **Action:** each moves the target one film left or right.

### 7. Footer

- **Position:** fixed 32px from the sides and 26px from the bottom, `justify-content: space-between`.
- **Left:** "© LEON VASARI. ALL RIGHTS RESERVED."
- **Right:** "FB / TW", where FB and TW are links in ink with no underline.
- Both are `.lbl`.

### 8. Custom cursor

- **Element:** 58 × 58px, fixed, centred on the pointer with −29px margins, `z-index 100`, shown only on fine pointers.
- **Parts:**
  - A 1.5px ink ring (border radius 50 %).
  - A 6px ink centre dot.
  - A hidden label "OPEN" over "開く" in Inter Tight 600, 10px, line height 1.25, letter-spacing .1em, white, centred.
- **Movement:** it follows the mouse with exponential smoothing, `1 − e^(−16·dt)` per frame, positioned with `translate3d`.

| State | When | Ring | Dot | Label |
|---|---|---|---|---|
| default | anywhere else | scale 1, ink border, transparent | scale 1 | hidden (scale 0) |
| `.spine` | over a non-active tape | scale .72 | 1 | hidden |
| `.btn` | over any button or link outside the shelf | scale .55 | scale 0 | hidden |
| `.open` | over the open cover (the tilt test above) | scale 1.75, cobalt fill, cobalt border | scale 0 | scale 1 |

- **Transitions:** the ring's transform, background colour and border colour run over `.5s / .4s / .4s var(--ease)`. The dot and label scale over `.4s / .45s`. Entering the cover, the ring swells into a cobalt disc and "OPEN / 開く" pops out of its centre.

## Data: the twelve films (chronological shelf order)

| # | id | Title | Romaji | Kanji | Year | Genre | Minutes | Synopsis |
|---|---|---|---|---|---|---|---|---|
| 0 | valley | The Silent Valley | SHIZUKANA TANI | 静かな谷 | 1958 | Drama | 104 | A schoolteacher returns to the mountain village that exiled her father, and finds the valley has kept every one of its secrets. |
| 1 | bluehour | The Blue Hour | AO NO TOKI | 青の刻 | 1962 | Romance | 97 | Over one long evening in a harbour town, a widow and a stranger trade small lies until the light runs out. |
| 2 | river | River of Salt | SHIO NO KAWA | 塩の川 | 1964 | Drama | 121 | Two brothers drag a salt barge downriver to a city that no longer wants anything they carry. |
| 3 | summer | The Last Summer | SAIGO NO NATSU | 最後の夏 | 1966 | Drama | 109 | The summer before the dam floods their village, three friends set fire to everything they cannot take with them. |
| 4 | green | The Green Road | MIDORI NO MICHI | 緑の道 | 1969 | Mystery | 101 | A surveyor mapping a forest road keeps finding the same footprints, always one day ahead of him. |
| 5 | noon | Noon in Ashes | HAI NO SHOGO | 灰の正午 | 1971 | Western | 112 | A rider crosses a white desert to settle an old debt, and learns too late who sent him. |
| 6 | observer | The Observer | KANSATSUSHA | 観察者 | 1973 | Thriller | 96 | A night watchman begins to suspect that the building he guards has started watching him back. |
| 7 | birds | The Fallen Birds | OCHITA TORI | 落ちた鳥 | 1975 | Drama | 118 | When the birds stop singing over a frontier town, the mayor's daughter is the only one who goes looking for the reason. |
| 8 | storm | Light in the Storm | ARASHI NO HI | 嵐の灯 | 1978 | Drama | 127 | A lighthouse keeper and his son wait out a three-day storm with a shipwrecked sailor who will not give his name. |
| 9 | tide | The Long Tide | NAGAI SHIO | 長い潮 | 1981 | Drama | 99 | A fisherman's wife counts the tides on the harbour wall while her husband's boat fails to come home. |
| 10 | war | A Quiet War | SHIZUKANA SENSO | 静かな戦争 | 1985 | Comedy | 103 | Two neighbours fight a silent war over a garden wall for thirty years, and neither will say how it began. |
| 11 | door | Red Door | AKAI TOBIRA | 赤い扉 | 1989 | Thriller | 114 | A projectionist follows a reel of unknown film through the corridors of a cinema on its final night. |

The page opens on **Noon in Ashes** (index 5, in the middle copy, so `s = 5 + 12 = 17`).

## Motion engine

### State
- `s`: the current scroll position in tape units.
- `T`: the target.
- `hover`: the hovered virtual index, or −1.
- `active`: the film index currently in the caption.
- `mx, my`: the raw pointer; `cx, cy`: the smoothed cursor.
- `tiltX, tiltY`, `onCover`, `isOpen`.

### Each frame
- **Time step:** `dt` is clamped to 50ms.
- **Spring:** `s += (T − s) × (1 − e^(−k·dt))`, with `k = 5.2` normally and `18` while dragging. It snaps when within 1e−4. A one-step move settles in about 0.9s, and multi-step jumps glide through every tape in between.
- **Normalising:** if `s` drifts beyond ±4 full loops, both `s` and `T` shift by whole loops.
- **Caption:** the active film is `round(s) mod 12`. When it changes, run the caption swap with `dir = sign(T − s)`.

### Inputs
- **Click a tape:** if it is the active one (`|r| < .5`), open the detail. Otherwise set `T = round(T + r)`, so the shelf glides that tape to the centre.
- **Arrows:** `T = round(T) ± 1`.
- **Keyboard:** Left and Right do the same. Enter opens the detail when focus is on the body. Escape closes it.
- **Decade tabs:** jump to the first film of that decade by the shortest way round the loop. "ALL" jumps to The Silent Valley.
- **Wheel:** both axes; use whichever delta is larger. `T += delta / (ws + gap) × 0.5`. After 160ms of no wheel input, `T` snaps to the nearest integer. Wheel input is ignored while the detail is open.
- **Drag:**
  - `pointerdown` on the shelf records the start x and `T`.
  - Once the pointer moves more than 5px it becomes a drag: `T = T0 − dx / (ws + gap)`, with the faster spring.
  - `pointerup` snaps `T` to the nearest integer.
  - A drag suppresses the click on the tape it ended over.

## Opening a film: paper sheet and ink reveal

The detail is a fixed full-screen `.detail` dialog (`z-index 60`, `--sheet` background, `visibility hidden` until opened).
- **Grid:** two equal columns with a `4vw` gap and padding `110px 6vw 56px 7vw`.

### Contents

- **Close button:** a boxed `.lbl` "CLOSE / 閉じる" at the top left (32px, 31px).
- **Logo:** a copy of the cobalt logo, centred in an 84px top band.
- **Left column**, centred vertically, `max-width 520px`, 18px gap, top to bottom. Every line is wrapped in its own overflow mask:
  1. The cobalt subtitle `.lbl`, "ROMAJI / kanji".
  2. The title, Newsreader 400, `clamp(44px, 5.4vw, 84px)`, line height 1, letter-spacing −.025em.
  3. The meta `.lbl` in muted grey, "YEAR / GENRE / N MIN" (e.g. "1971 / WESTERN / 112 MIN").
  4. The synopsis, Newsreader 400, 17px, line height 1.5, `max-width 42ch`.
  5. An italic credit, Newsreader italic, 15px, muted: "Written and directed by Leon Vasari. 監督作品".
  6. A 44px boxed button, cobalt border and text, 0 20px padding, 10px top margin: "WATCH THE FILM / 映画を見る".
- **Right column: the poster.** Height `min(100%, 78vh)` with aspect ratio 474/900, centred.
  - It is an inline SVG with viewBox `0 0 474 900` holding one clipped `<image>` of the film's cover crop (see Media), masked by an ink mask.
  - **The ink mask:** a `<mask>` in user space (−200, −200, 874 × 1300) containing a group of seven white circles.
  - **Ink filter on that group:** `feTurbulence` fractalNoise, baseFrequency .011, 3 octaves, seed 7, feeding an `feDisplacementMap` with scale 120 on the R and G channels. The circles' edges become ragged, bleeding blots.

| Blob | cx | cy | Delay (ms) |
|---|---|---|---|
| 1 | 150 | 330 | 0 |
| 2 | 340 | 600 | 120 |
| 3 | 250 | 120 | 220 |
| 4 | 90 | 760 | 300 |
| 5 | 400 | 250 | 360 |
| 6 | 260 | 860 | 420 |
| 7 | 230 | 470 | 180 |

### Open sequence (`openDetail`)

1. **Prepare.**
   - Snap `T` to an integer and fill the detail texts from the active film.
   - Point the poster `<image>` at its cover's sheet, positioned so only its crop box shows (see Media).
   - Reset all blob radii to 0.
   - Read the screen rect of the active tape's cover face (`getBoundingClientRect`, which gives the projected 3D box).
2. **The sheet grows out of the cover.**
   - Make the dialog visible and set its `transform-origin` to the cover's centre.
   - Animate it with the Web Animations API over **1050ms**, `cubic-bezier(.76,0,.18,1)`, `fill both`.
   - From `clip-path: inset(top right bottom left round 3px)`, matching the cover rect, with `transform: rotate(−4.5deg)`.
   - To `clip-path: inset(0 0 0 0 round 0)` with `rotate(0)`.
   - A blank rectangle of paper the exact size and tilt of the cover straightens and expands until it covers the screen.
3. **Text rises.** Every masked line slides from `translateY(110%)` to 0 over **900ms**, `cubic-bezier(.2,.8,.2,1)`. Delays are `620ms + index × 75ms`, so the lines arrive one after another.
4. **The poster bleeds in.**
   - Starting 520ms after open, a rAF loop grows each circle's radius from 0 to 720 over **1250ms** after its own delay, with an ease-out cubic `1 − (1 − p)³`.
   - The cover appears as spreading ink blots that merge into the full poster.
   - The loop stops after 2.4s.
5. **Hide the rest.** The play ring scales to 0, and the cursor drops its OPEN and spine states while over the sheet.

### Close (`closeDetail`: the Close button or Escape)

- Animate the sheet back from full screen to the current cover rect, with `rotate(−4.5deg)`, over **850ms** with the same ease.
- When it finishes, hide the dialog and cancel all its animations so the next open starts fresh.

## Responsive (≤ 767px)

- `--H: min(60vw, 40svh)`. Every tape dimension follows from it.
- **Top bar:** 64px tall, 16px padding. The logo becomes 17px over 7.5px. Labels are 9px. **The career label is hidden.**
- **Tabs:** sit at `50% − H/2 − 70px`, with 0 7px padding and 9px text.
- **Caption title:** 24px.
- **Arrows:** 6px from the edges.
- **Footer:** 16px sides, 18px bottom, 9px labels.
- **Detail:** a single column that scrolls vertically.
  - Padding `84px 22px 40px`, 24px gap.
  - The poster moves first and is `46svh` tall.
  - Title 42px, synopsis 16px. The Close button sits at 16px, 21px, and the logo band is 64px.
- **Touch:** the custom cursor is not shown. Dragging the shelf with a finger scrubs it, because the shelf uses `touch-action: pan-y`.

## Reduced motion

With `prefers-reduced-motion: reduce`:
- The scroll spring and hover lift become instant (k = 1), so tapes snap between states.
- Caption swaps replace the text without sliding.
- The sheet open, close and text rises run with 1ms duration and no delay.
- The ink starts 5s in the past, so the poster is fully visible at once.

## Accessibility

- The tabs are a `<nav aria-label="Decades">` and the shelf is a `<section aria-label="Filmography shelf">`.
- The caption container is `aria-live="polite"`, so film changes are announced.
- Arrow and play buttons have `aria-label`s ("Previous film", "Next film", "Open film").
- The detail is `role="dialog" aria-modal="true"`. The poster SVG is `aria-hidden`.
- All controls are real `<button>`s and links.

## Acceptance checklist

- On load, Noon in Ashes is turned out at the centre: tilted −4.5°, lifted and casting a shadow. The other eleven spines repeat endlessly on both sides, about 13 visible at 1440px.
- Clicking a spine two places to the right glides the shelf: the open tape turns back into a spine while the next ones turn out in passing, and the caption rolls through each title.
- The cobalt tab block slides to the new decade.
- The cursor ring shrinks over spines and becomes a cobalt "OPEN / 開く" disc over the cover, which leans towards it.
- Clicking the cover grows a tilted sheet of paper out of it to full screen. The detail text rises line by line, and the poster bleeds in as ragged ink blots.
- There are no opacity fades anywhere.


Text animation 03:


# Maison Vell — Runway Depth Lookbook (exact recreation prompt)

Give me a single-file, full-viewport fashion page called **Maison Vell**. Six models stand in one line that recedes from the right of the screen into a blurred distance on the left. Dragging, scrolling or pressing the arrow keys walks the whole line forward: the front model grows and slides out behind the product column, everyone else takes the next place, and a new model arrives out of the haze at the back. The product column on the right scrolls in sync, and a big look number rolls over at bottom left. It loops forever.

Plain HTML, CSS and one vanilla script in one file, with no libraries. The only external resources are the Google Fonts and the two image sheets below. Reproduce every value, string and timing exactly, and use the complete code at the end as the source of truth.

Six rules define it:
1. **One number drives everything.** `p` is the current look position as a float. Each model's depth is `d = wrap(i - p, 6)`, moved into the range -1 to 5. Model, product column and look number are all computed from `p` alone.
2. **Depth is a table, not a formula.** Each model's position, size, blur and opacity are read from seven stops, one per depth from -1 to 5, and interpolated linearly.
3. **Two sprite sheets, cropped with SVG.** All six models come from one transparent image and all twelve products from another. Each is shown through an inline `<svg viewBox>` holding a nested `<svg>` so nothing outside the box can ever show.
4. **Layers scale, they do not resize.** Models are laid out once at 1.2 × stage height and only `transform` changes, so they stay sharp. Blur is divided by the scale so it looks the same on screen at any depth.
5. **Drag is direct, release snaps.** During a drag `target` follows the pointer. On release, or 150 ms after the wheel stops, it rounds to a whole look. `p` always chases `target` with an exponential ease.
6. **The product column wraps.** Twelve cards sit on one looping track, so scrolling never ends.

---

## 1. Page basics

- Title: `Maison Vell`
- Meta description: `A runway lookbook where six looks stand in a line into the distance and every drag brings the next one to the front.`
- Fonts: `https://fonts.googleapis.com/css2?family=Inter:wght@400;500&family=Michroma&display=swap`, with preconnects to fonts.googleapis.com and fonts.gstatic.com (crossorigin). The supplied standalone file embeds the latin woff2 files as base64 instead.
- Michroma, uppercase, wide-tracked, for the logo, tabs, nav, headings, labels and look number. Inter for the paragraph and prices.
- Colours: ink `#16191f`, mid `#737b86`, dim `#a4adb8`, white page, rail `#f3f6fa`.
- Unit: `--u:min(calc(100vw/1600),calc(100vh/900))`, which becomes `1px` at 820px wide and below.
- `.page` is `100svh` tall, `min-height:520px`, a grid of header then main. Body has `overflow:hidden`.
- A fixed `.wait` cover in `#f1f5fa` fades over .5s once both sheets have decoded and fonts are ready.

## 2. Images (use these exact URLs)

1. Models sheet, transparent, 3840 × 2160: `https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261102_042056_1a704ff7-b0e5-4a9f-bbda-62392b819fb6.png&w=3840&q=85`
2. Products sheet, transparent, 2400 wide: `https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261102_042057_080e85b0-b4aa-4072-8eb9-2304c7baf42b.png&w=2400&q=85`

Models are measured on a 960 × 540 sheet, all with `y` from 48 to 496. Their `x` ranges in order: 12–176 (blush feather jacket and satin trousers), 178–330 (sage pleated gown), 331–470 (champagne satin trench), 476–633 (blush billow blouse and trousers), 634–767 (powder-blue coat), 767–956 (ivory ruffle gown).

Products are measured on a 960 × 720 sheet (x0, x1, y0, y1, name, price):

| Look | Piece | Box | Name | Price |
|---|---|---|---|---|
| 15 | 1 | 26, 224, 28, 214 | Feather Jacket | $2,900 |
| 15 | 2 | 304, 412, 22, 236 | Satin Wide Leg Trousers | $1,450 |
| 16 | 1 | 530, 666, 12, 242 | Pleated Dress | $2,200 |
| 16 | 2 | 752, 922, 100, 146 | Gold Waist Belt | $420 |
| 17 | 1 | 70, 176, 246, 466 | Satin Trench Dress | $2,350 |
| 17 | 2 | 294, 422, 294, 432 | Top Handle Bag | $980 |
| 18 | 1 | 508, 688, 240, 452 | Billow Sleeve Blouse | $860 |
| 18 | 2 | 780, 890, 252, 466 | Tie Waist Trousers | $740 |
| 19 | 1 | 64, 178, 484, 698 | Powder Long Coat | $1,980 |
| 19 | 2 | 316, 396, 482, 698 | Ivory Straight Trousers | $690 |
| 20 | 1 | 530, 672, 508, 682 | Sculpted Ruffle Top | $1,120 |
| 20 | 2 | 754, 916, 484, 700 | Pleated Maxi Skirt | $1,340 |

## 3. Header

- White, padding 20u top, 46u sides, 15u bottom. First row is a `1fr auto 1fr` grid.
- Logo `Maison Vell`, 15.5u, tracking .2em.
- Tabs, 14.5u, tracking .14em, gap 48u, dim colour: `Runway` (active, ink), `The Maison`, `Lookbook`, `Shop`.
- Right, 9.5u, tracking .12em, gap 22u: `Login`, search icon, heart icon, bag icon, `Cart (0)`. The icons are 17u outline SVGs.
- Second row, 17u below, centred, 9.5u, tracking .14em, gap 60u: `Collections`, `Clothing`, `Lookbook`, `Beauty`, `Accessories`, `Our World`.

## 4. Stage

- `main` is a grid of the stage plus a `372u` rail.
- Stage background: `linear-gradient(transparent 60%,rgba(255,255,255,.72) 100%)` over `linear-gradient(90deg,#f1f5fa 0%,#e7eff6 38%,#eef4f9 62%,#f6f9fc 100%)`. It has `cursor:none`, `touch-action:pan-y` and no text selection.
- Top left at 46u, 36u: `Spring Summer 2027`, 22u, tracking .16em. Then the paragraph 16u below, 14u Inter, line height 1.62, mid colour, 390u wide: `A study in softness and strength. The new season collection from Maison Vell blends delicate textures and modern silhouettes, crafted for a more beautiful tomorrow.`
- Bottom left at 46u, 44u: `Look` and the rolling number, 29u on a 38u line, tracking .14em. Then the underlined link `Shop the look`, 9.5u, 13u below.
- Rolling number: a 38u tall window with overflow hidden holding 15, 16, 17, 18, 19, 20, 15 stacked. It moves by `-wrap(p,6) × line height`, so the numbers slide past each other.
- Each model has a soft elliptical floor shadow: `radial-gradient(closest-side,rgba(70,85,105,.24),transparent)`, 84% wide, 3.6% tall, just below the feet.

## 5. Depth table

All are fractions of stage size. Depth runs -1, 0, 1, 2, 3, 4, 5. At depth -1 the model leaves past the rail, and at depth 5 it arrives from nothing.

| Value | -1 | 0 | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|---|---|
| Centre X (`KX`) | 1.2 | .744 | .496 | .346 | .235 | .15 | .085 |
| Feet Y (`KF`) | 1.14 | .89 | .777 | .704 | .651 | .616 | .59 |
| Height (`KH`) | 1.18 | .832 | .574 | .436 | .334 | .258 | .19 |
| Blur px (`KB`) | 0 | 0 | 1.5 | 4 | 8 | 12 | 17 |
| Opacity (`KO`) | 1 | 1 | 1 | 1 | .86 | .5 | 0 |

`z-index` is `100 - round(d*10)`. Filter and opacity are written only when they change, and the page only repaints while `p` is moving.

## 6. Interaction

- Each frame, `p += (target-p) * (1-exp(-dt*.0072))`, with `dt` capped at 50 ms. It snaps to `target` under .0004.
- **Drag:** `target = start + dx / max(150, stageWidth*.2)`. Dragging right moves the line forward. Release rounds `target`.
- **Click:** a press that moves under 6px on a model in the line jumps to that look.
- **Wheel:** adds `clamp(deltaY+deltaX,-120,120)/420`, then rounds 150 ms after the last event.
- **Keys:** Right and Down go forward one look, Left and Up go back one. The stage is focusable.
- **Reduced motion:** `p` jumps straight to `target`.
- **Ring cursor:** 46u circle, 2.5u `#16191f` border, following the pointer at 32% per frame. While dragging it becomes an 84u × 34u pill over .22s with `cubic-bezier(.2,.8,.2,1)`. It shows only for a mouse.

## 7. Product rail

- Background `#f3f6fa`, overflow hidden. Exactly three cards fit, each `rail height / 3`. Odd cards are white.
- Card position: `y = wrap(i*card - p*2*card, 12*card)`, moved up by a full track if past the last slot, so each look's first piece lands at the top.
- Card padding 18u top and bottom, 24u sides. Heart button top left at 22u, 18u. Product image fills the remaining space, contained. Name 9.5u Michroma, tracking .14em. Price 12.5u Inter. Plus button 26u at bottom right, drawn with two 1.5px bars, rotating 90° on hover.
- Heart toggles `aria-pressed` and fills `#d8a7a0`. Plus adds one to the cart count.

## 8. Phones (820px and below)

`--u:1px`. Tabs, second nav row and all account items except the cart are hidden. Header padding 14px 16px 12px. `main` becomes a `1fr 190px` grid with the rail along the bottom as a horizontal track of 160px cards using `translate3d(x,0,0)`. The heading is 17px, the paragraph is hidden, the look number is 22px on a 30px line, and the ring is removed.

---

## Complete code

This is the finished page. Build exactly this.

```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Maison Vell</title>
<meta name="description" content="A runway lookbook where six looks stand in a line into the distance and every drag brings the next one to the front.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500&family=Michroma&display=swap" rel="stylesheet">
<style>
:root{--u:min(calc(100vw/1600),calc(100vh/900));--ink:#16191f;--mid:#737b86;--dim:#a4adb8;--line:#e6ebf0;--ice:#e9f0f7}
*{box-sizing:border-box;margin:0;padding:0}
html,body{height:100%;background:#fff}
body{font-family:Inter,system-ui,sans-serif;color:var(--ink);-webkit-font-smoothing:antialiased;overflow:hidden}
a{color:inherit;text-decoration:none}
button{font:inherit;color:inherit;background:none;border:0;cursor:pointer}
ul{list-style:none}
.wide{font-family:Michroma,sans-serif;text-transform:uppercase}
.page{height:100svh;min-height:520px;display:grid;grid-template-rows:auto 1fr;background:#fff}
header{position:relative;z-index:5;background:#fff;padding:calc(20*var(--u)) calc(46*var(--u)) calc(15*var(--u))}
.r1{display:grid;grid-template-columns:1fr auto 1fr;align-items:center}
.brand{font-size:calc(15.5*var(--u));letter-spacing:.2em}
.tabs{display:flex;gap:calc(48*var(--u));font-size:calc(14.5*var(--u));letter-spacing:.14em;color:var(--dim)}
.tabs a{transition:color .25s}
.tabs a:hover,.tabs .on{color:var(--ink)}
.acct{justify-self:end;display:flex;align-items:center;gap:calc(22*var(--u));font-size:calc(9.5*var(--u));letter-spacing:.12em}
.acct svg{width:calc(17*var(--u));height:calc(17*var(--u));fill:none;stroke:currentColor;stroke-width:1.5}
.r2{display:flex;justify-content:center;gap:calc(60*var(--u));margin-top:calc(17*var(--u));font-size:calc(9.5*var(--u));letter-spacing:.14em}
.r2 a{transition:color .2s}.r2 a:hover{color:var(--mid)}
main{position:relative;display:grid;grid-template-columns:1fr calc(372*var(--u));min-height:0}
.stage{position:relative;overflow:hidden;min-width:0;touch-action:pan-y;user-select:none;-webkit-user-select:none;cursor:none;
  background:linear-gradient(transparent 60%,rgba(255,255,255,.72) 100%),linear-gradient(90deg,#f1f5fa 0%,#e7eff6 38%,#eef4f9 62%,#f6f9fc 100%)}
.line{position:absolute;inset:0}
.m{position:absolute;left:0;top:0;transform-origin:0 0;will-change:transform,filter;cursor:none}
.m svg{display:block;position:relative;width:100%;height:100%}
.m:before{content:"";position:absolute;left:8%;right:8%;bottom:-1.6%;height:3.6%;border-radius:50%;background:radial-gradient(closest-side,rgba(70,85,105,.24),transparent)}
.intro{position:absolute;z-index:2;left:calc(46*var(--u));top:calc(36*var(--u));width:calc(390*var(--u));pointer-events:none}
.intro h2{font-weight:400;font-size:calc(22*var(--u));line-height:1.2;letter-spacing:.16em;white-space:nowrap}
.intro p{margin-top:calc(16*var(--u));font-size:calc(14*var(--u));line-height:1.62;letter-spacing:.012em;color:var(--mid)}
.tag{position:absolute;z-index:2;left:calc(46*var(--u));bottom:calc(44*var(--u))}
.look{display:flex;font-size:calc(29*var(--u));line-height:calc(38*var(--u));letter-spacing:.14em;gap:.5em;pointer-events:none}
.win{height:calc(38*var(--u));overflow:hidden}
.roll{display:block;will-change:transform}
.roll b{display:block;font-weight:400;height:calc(38*var(--u))}
.shop{display:inline-block;margin-top:calc(13*var(--u));font-size:calc(9.5*var(--u));letter-spacing:.14em;padding-bottom:calc(4*var(--u));border-bottom:1px solid currentColor}
.ring{position:absolute;z-index:4;left:0;top:0;width:calc(46*var(--u));height:calc(46*var(--u));margin:calc(-23*var(--u)) 0 0 calc(-23*var(--u));border:calc(2.5*var(--u)) solid #16191f;border-radius:99px;pointer-events:none;opacity:0;transition:width .22s cubic-bezier(.2,.8,.2,1),height .22s cubic-bezier(.2,.8,.2,1),margin .22s cubic-bezier(.2,.8,.2,1),opacity .2s}
.ring.show{opacity:1}
.ring.drag{width:calc(84*var(--u));height:calc(34*var(--u));margin:calc(-17*var(--u)) 0 0 calc(-42*var(--u))}
.rail{position:relative;overflow:hidden;background:#f3f6fa;min-height:0}
.card{position:absolute;left:0;top:0;width:100%;display:flex;flex-direction:column;padding:calc(18*var(--u)) calc(24*var(--u)) calc(18*var(--u));will-change:transform;background:#f3f6fa}
.card.alt{background:#fff}
.fav{position:absolute;left:calc(22*var(--u));top:calc(18*var(--u));width:calc(22*var(--u));height:calc(22*var(--u));z-index:1;color:var(--ink)}
.fav svg{width:100%;height:100%;fill:none;stroke:currentColor;stroke-width:1.4;transition:fill .2s}
.fav[aria-pressed=true] svg{fill:#d8a7a0;stroke:#b98179}
.shot{flex:1;min-height:0;display:block}
.shot svg{display:block;width:100%;height:100%}
.meta{display:grid;grid-template-columns:1fr auto;align-items:end;margin-top:calc(8*var(--u))}
.meta h3{font-weight:400;font-size:calc(9.5*var(--u));letter-spacing:.14em}
.meta span{display:block;grid-column:1;margin-top:calc(6*var(--u));font-size:calc(12.5*var(--u));color:var(--mid);letter-spacing:.03em}
.add{grid-column:2;grid-row:1/3;width:calc(26*var(--u));height:calc(26*var(--u));position:relative;transition:transform .2s}
.add:before,.add:after{content:"";position:absolute;left:50%;top:50%;width:calc(15*var(--u));height:1.5px;margin:-.75px 0 0 calc(-7.5*var(--u));background:var(--ink)}
.add:after{transform:rotate(90deg)}
.add:hover{transform:rotate(90deg)}
.wait{position:fixed;inset:0;z-index:9;background:#f1f5fa;transition:opacity .5s;pointer-events:none}
.wait.gone{opacity:0}
button:focus-visible,a:focus-visible{outline:2px solid var(--ink);outline-offset:3px}
@media (max-width:820px){
  :root{--u:1px}
  header{padding:14px 16px 12px}
  .r1{grid-template-columns:1fr auto}
  .tabs,.r2,.acct>a:not(:last-child){display:none}
  .brand{font-size:14px}
  main{grid-template-columns:1fr;grid-template-rows:1fr 190px}
  .stage{cursor:auto}.m{cursor:auto}.ring{display:none}
  .intro{left:16px;top:18px;width:calc(100% - 32px)}
  .intro h2{font-size:17px}
  .intro p{display:none}
  .tag{left:16px;bottom:18px}
  .look{font-size:22px;line-height:30px}.win,.roll b{height:30px}
  .card{width:160px;height:100%;padding:12px}
  .fav{left:10px;top:10px}
}
</style>
</head>
<body>
<div class="page">
  <header>
    <div class="r1">
      <a class="brand wide" href="#" aria-label="Maison Vell">Maison Vell</a>
      <nav class="tabs wide" aria-label="Sections"><a class="on" href="#" aria-current="page">Runway</a><a href="#">The Maison</a><a href="#">Lookbook</a><a href="#">Shop</a></nav>
      <div class="acct wide">
        <a href="#">Login</a>
        <a href="#" aria-label="Search"><svg viewBox="0 0 24 24"><circle cx="10.5" cy="10.5" r="6.5"/><path d="m15.5 15.5 5 5"/></svg></a>
        <a href="#" aria-label="Saved"><svg viewBox="0 0 24 24"><path d="M12 20S3.5 15 3.5 9A4.6 4.6 0 0 1 12 6.6 4.6 4.6 0 0 1 20.500 9C20.500 15 12 20 12 20Z"/></svg></a>
        <a href="#" aria-label="Bag"><svg viewBox="0 0 24 24"><path d="M5 8h14l1 13H4Z"/><path d="M9 10V6a3 3 0 0 1 6 0v4"/></svg></a>
        <a href="#">Cart (<span id="cart">0</span>)</a>
      </div>
    </div>
    <nav class="r2 wide" aria-label="Departments"><a href="#">Collections</a><a href="#">Clothing</a><a href="#">Lookbook</a><a href="#">Beauty</a><a href="#">Accessories</a><a href="#">Our World</a></nav>
  </header>
  <main>
    <section class="stage" id="stage" aria-label="Runway looks. Drag, scroll or use the arrow keys to change look." tabindex="0">
      <div class="line" id="line"></div>
      <div class="intro">
        <h2 class="wide">Spring Summer 2027</h2>
        <p>A study in softness and strength. The new season collection from Maison Vell blends delicate textures and modern silhouettes, crafted for a more beautiful tomorrow.</p>
      </div>
      <div class="tag">
        <div class="look wide" aria-live="polite"><span>Look</span><span class="win"><span class="roll" id="roll"></span></span></div>
        <a class="shop wide" href="#">Shop the look</a>
      </div>
      <div class="ring" id="ring"></div>
    </section>
    <aside class="rail" id="rail" aria-label="Pieces in this look"></aside>
  </main>
</div>
<div class="wait" id="wait"></div>
<script>
const MODELS='https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261102_042056_1a704ff7-b0e5-4a9f-bbda-62392b819fb6.png&w=3840&q=85';
const PIECES='https://images.higgs.ai/?default=1&output=webp&url=https%3A%2F%2Fd8j0ntlcm91z4.cloudfront.net%2Fuser_38xzZboKViGWJOttwIXH07lWA1P%2Fhf_20261102_042057_080e85b0-b4aa-4072-8eb9-2304c7baf42b.png&w=2400&q=85';
// each model's box on the 960 x 540 sheet: x0, x1
const LOOKS=[[12,176],[178,330],[331,470],[476,633],[634,767],[767,956]],Y0=48,Y1=496,FIRST=15;
// each piece's box on the 960 x 720 sheet: x0, x1, y0, y1, name, price
const ITEMS=[
  [26,224,28,214,'Feather Jacket','$2,900'],[304,412,22,236,'Satin Wide Leg Trousers','$1,450'],
  [530,666,12,242,'Pleated Dress','$2,200'],[752,922,100,146,'Gold Waist Belt','$420'],
  [70,176,246,466,'Satin Trench Dress','$2,350'],[294,422,294,432,'Top Handle Bag','$980'],
  [508,688,240,452,'Billow Sleeve Blouse','$860'],[780,890,252,466,'Tie Waist Trousers','$740'],
  [64,178,484,698,'Powder Long Coat','$1,980'],[316,396,482,698,'Ivory Straight Trousers','$690'],
  [530,672,508,682,'Sculpted Ruffle Top','$1,120'],[754,916,484,700,'Pleated Maxi Skirt','$1,340']];
// depth stops from d = -1 (leaving past the rail) to d = 5 (arriving out of the haze)
const KX=[1.2,.744,.496,.346,.235,.15,.085],KF=[1.14,.89,.777,.704,.651,.616,.59],KH=[1.18,.832,.574,.436,.334,.258,.19],
      KB=[0,0,1.5,4,8,12,17],KO=[1,1,1,1,.86,.5,0];
const N=LOOKS.length,$=id=>document.getElementById(id),calm=matchMedia('(prefers-reduced-motion:reduce)').matches;
const stage=$('stage'),rail=$('rail'),ring=$('ring'),roll=$('roll'),line=$('line');
const NS='http://www.w3.org/2000/svg',wrap=(x,n)=>((x%n)+n)%n;
function crop(href,x0,y0,w,h,sheetW,sheetH){
  const s=document.createElementNS(NS,'svg');s.setAttribute('viewBox',`${x0} ${y0} ${w} ${h}`);s.setAttribute('aria-hidden','true');
  const f=document.createElementNS(NS,'svg');[['x',x0],['y',y0],['width',w],['height',h],['viewBox',`${x0} ${y0} ${w} ${h}`]].forEach(([k,v])=>f.setAttribute(k,v));
  const i=document.createElementNS(NS,'image');i.setAttribute('href',href);i.setAttribute('width',sheetW);i.setAttribute('height',sheetH);f.append(i);s.append(f);return s;
}
const people=LOOKS.map(([a,b],i)=>{
  const e=document.createElement('div');e.className='m';e.dataset.i=i;e.append(crop(MODELS,a,Y0,b-a,Y1-Y0,960,540));line.append(e);
  return{e,r:(b-a)/(Y1-Y0),f:'',o:''};
});
const cards=ITEMS.map(([a,b,c,d,name,price],i)=>{
  const e=document.createElement('article');e.className='card'+(i%2?' alt':'');
  e.innerHTML=`<button class="fav" aria-pressed="false" aria-label="Save ${name}"><svg viewBox="0 0 24 24"><path d="M12 20S3.5 15 3.5 9A4.6 4.6 0 0 1 12 6.6 4.600 4.600 0 0 1 20.500 9C20.500 15 12 20 12 20Z"/></svg></button><span class="shot"></span><div class="meta"><h3 class="wide">${name}</h3><span>${price}</span><button class="add" aria-label="Add ${name} to cart"></button></div>`;
  e.querySelector('.shot').append(crop(PIECES,a,c,b-a,d-c,960,720));rail.append(e);return e;
});
for(let i=0;i<=N;i++){const b=document.createElement('b');b.textContent=FIRST+i%N;roll.append(b)}
let cart=0;
rail.addEventListener('click',e=>{
  const f=e.target.closest('.fav');if(f)f.setAttribute('aria-pressed',f.getAttribute('aria-pressed')!=='true');
  if(e.target.closest('.add'))$('cart').textContent=++cart;
});

let W=0,H=0,base=0,cardS=0,side=false,dirty=true,p=0,target=0,last=0;
function size(){
  W=stage.clientWidth;H=stage.clientHeight;base=H*1.2;side=innerWidth<=820;
  people.forEach(m=>{m.e.style.width=base*m.r+'px';m.e.style.height=base+'px'});
  cardS=side?160:rail.clientHeight/3;
  cards.forEach(c=>c.style.height=side?'100%':cardS+'px');
  roll.style.setProperty('--h',roll.firstChild.getBoundingClientRect().height);
  dirty=true;
}
addEventListener('resize',size);

function paint(){
  people.forEach((m,i)=>{
    let d=wrap(i-p,N);if(d>N-1)d-=N;
    const k=clamp(d+1,0,6),a=Math.floor(k),b=Math.min(6,a+1),t=k-a,mix=A=>A[a]+(A[b]-A[a])*t;
    const h=mix(KH)*H,s=h/base,w=h*m.r,x=mix(KX)*W-w/2,y=mix(KF)*H-h;
    m.e.style.transform=`translate3d(${x.toFixed(1)}px,${y.toFixed(1)}px,0) scale(${s.toFixed(4)})`;
    const f=mix(KB)/s,fs=f<.2?'none':`blur(${f.toFixed(1)}px)`,o=mix(KO).toFixed(3);
    if(fs!==m.f){m.f=fs;m.e.style.filter=fs}
    if(o!==m.o){m.o=o;m.e.style.opacity=o}
    m.e.style.zIndex=100-Math.round(d*10);
  });
  const all=cardS*ITEMS.length;
  cards.forEach((c,i)=>{
    let y=wrap(i*cardS-p*2*cardS,all);if(y>all-cardS)y-=all;
    c.style.transform=side?`translate3d(${y.toFixed(1)}px,0,0)`:`translate3d(0,${y.toFixed(1)}px,0)`;
  });
  roll.style.transform=`translate3d(0,${(-wrap(p,N)*roll.firstChild.offsetHeight).toFixed(1)}px,0)`;
}
const clamp=(x,a,b)=>Math.min(b,Math.max(a,x));

function frame(now){
  const dt=Math.min(50,now-last)||16;last=now;
  const was=p;
  if(calm)p=target;else p+=(target-p)*(1-Math.exp(-dt*.0072));
  if(Math.abs(target-p)<.0004)p=target;
  if(p!==was||dirty){dirty=false;paint()}
  cx+=(mx-cx)*.32;cy+=(my-cy)*.32;
  ring.style.transform=`translate3d(${cx.toFixed(1)}px,${cy.toFixed(1)}px,0)`;
}

let mx=0,my=0,cx=0,cy=0,down=false,sx=0,st=0,moved=0,wheelT=0;
const PULL=()=>Math.max(150,W*.2);
stage.addEventListener('pointerenter',e=>{if(e.pointerType==='mouse')ring.classList.add('show')});
stage.addEventListener('pointerleave',()=>ring.classList.remove('show'));
stage.addEventListener('pointermove',e=>{
  const r=stage.getBoundingClientRect();mx=e.clientX-r.left;my=e.clientY-r.top;
  if(!down)return;
  const dx=e.clientX-sx;moved=Math.max(moved,Math.abs(dx));target=st+dx/PULL();
});
stage.addEventListener('pointerdown',e=>{
  if(e.target.closest('a'))return;
  down=true;sx=e.clientX;st=target;moved=0;stage.setPointerCapture(e.pointerId);ring.classList.add('drag');
});
function release(e){
  if(!down)return;down=false;ring.classList.remove('drag');
  if(moved<6){
    const hit=document.elementsFromPoint(e.clientX,e.clientY).find(x=>x.classList&&x.classList.contains('m'));
    if(hit){let d=wrap(+hit.dataset.i-target,N);d=Math.round(d);if(d>0&&d<N)target=Math.round(target)+d}
  }else target=Math.round(target);
}
stage.addEventListener('pointerup',release);stage.addEventListener('pointercancel',release);
stage.addEventListener('wheel',e=>{
  e.preventDefault();target+=clamp(e.deltaY+e.deltaX,-120,120)/420;
  clearTimeout(wheelT);wheelT=setTimeout(()=>{target=Math.round(target)},150);
},{passive:false});
addEventListener('keydown',e=>{
  if(['ArrowRight','ArrowDown'].includes(e.key)){e.preventDefault();target=Math.round(target)+1}
  if(['ArrowLeft','ArrowUp'].includes(e.key)){e.preventDefault();target=Math.round(target)-1}
});

function loop(t){frame(t);requestAnimationFrame(loop)}
Promise.all([MODELS,PIECES].map(u=>{const i=new Image;i.src=u;return i.decode().catch(()=>{})})).then(()=>document.fonts.ready).then(()=>{
  size();paint();$('wait').classList.add('gone');
});
size();requestAnimationFrame(loop);
</script>
</body>
</html>
```



Text animation 05:

Make a dynamic 40-second motion graphics video on Distilbook that shows what an incredible motion designer you are, like it's your showreel - go all out. Use the Oppenheimer theme music as inspiration, but compose it yourself.



Text animation 06:

We're going to try a little test. Do you think you could render a recipe motion graphic animation using javascript or html (w/e you think will produce the best) to show the full recipe from start to finish (empty glass to completed cocktail) - Explainer video style - Showing the recipe ingreidents + measurements as they're going into the cup. Should be a 30s video.


Text animation 07:

make a dynamic 15-second motion graphics video that shows what an incredible motion designer you are, like it's your showreel for a résumé. go all out


Text animation 08:
Make a showreel-style motion graphics video for my portfolio website, https://t.co/xZFGCqi73s, using Remotion. It should show what I do as a developer relations engineer, like a showreel for my résumé.

- Use as much of the real website as possible: capture the pages and sections in a browser (home, Ask, package pages, Hire, mobile view, dark mode) and animate them inside browser and phone frames.
- Show the site's chat answering real questions about my work, with the questions and answers large and bold. Use only facts and numbers that are on the site.
- Follow premium brand rules: three colours and the site's own fonts, one idea per shot, key objects centred, space to breathe, eased motion only, smooth transitions instead of hard cuts, and a rhythm that speeds up and slows down with the story.
- Add music at about 120 BPM (elite, kinetic, sophisticated) and cut every scene on the beat. No extra sound effects.
- 1920×1080, about 90 to 100 seconds, ending on the website and my contact email.
Text animation 09:
make a dynamic 15-second motion graphics video for RedSeed AI (Replace with your Project) that shows what an incredible motion designer you are, like it's your showreel for a résumé. go all out.
Text animation 10:
Create a high energy launch video, showing live stats from the website, show that users can play on desktop and mobile and multiple themes, if need, give me a prompt to generate the song using Suno
Text animation 11:
make a dynamic 15-second motion graphics video that shows what an incredible work Studio1 is doing, you will get relevant info from case study, create like it's a good showreel for a Studio1 intro launch. go all out.
Text animation 12:
Use Python to generate a 9:16 chaotic brain rot video with excellent motion + sound design and render it using ffmpeg. Put your own personal spin on it so it’s aligned with Anthropic’s new launch. Also fully express what it’s like to be a very creative LLM used by me every day from your POV to give it some extra personality.
Text animation 13:
制作一段 15 秒的动态图形视频，展示你是一位多么出色的动态设计师，就像是你简历上的作品集一样，使用任何你认为能产出最佳效果的工具或技术。你拥有完全的创作自由，优先追求卓越的视觉设计、大胆的艺术指导、引人注目的构图和富有力量的动态表现，让每一秒都有价值。全力以赴。
Text animation 14:
I Want you to make a modern slick and punchy video for https://t.co/a3zrq7DV3N with an example of a user creating a chatgpt ads campaign, then connecting their metrics, understanding attribution, then connecting a voice agent to it, the agent responding, then doing follow up, adding humans in the loop and then providing analytics.
Text animation 15:
make a 15-second motion graphics product ad: paste a YouTube video, get every word.
Text animation 16:
make a dynamic 20-second motion graphics video that shows what an incredible our email verify tool is, put all the use case you can imagine. go all out'
i want you to make it really modern and saas style. inspiration is yc videos and claude social videos
Text animation 17:
Research Distilbook.Make a dynamic 40-second motion graphics video on Distilbook that shows what an incredible motion designer you are. like it's your showreel - Go all out.
Text animation 18:
make a dynamic 15-second motion graphics video that shows what an incredible motion designer you are, like it's your showreel for a résumé. go all out.
Text animation 19:
make a 15-second showreel about my website. Go all out.
Text animation 20:
Make a dynamic 30-second motion graphics video that shows what an incredible motion designer you are, like it's your showreel for a résumé. go all out.  Make it a video to introduce https://t.co/xdCXEdKZRq Use actual product screenshot/logo/assets Must have music and motion must match the music  Do it like a real professional production video, not like a demo or prototype. Add more animation and motion design; avoid using screenshots as raw; instead, break them down into components/icons so we can animate those too. Make the motions more juicy. Use the best motion design techniques you can.
Text animation 21:
[Note: the creator shared a partial prompt. Wording below is theirs.]

GOAL:
Create a 14.5-second, cinematic 3D fly-through of my landing page at 1440×1152, 60fps, that ends on my logo.

MOTION:
Inputs: Landing page URL, brand name, logo as SVG (mark and wordmark as separate shapes), the one simple shape in the mark (a square, a dot or a bar) that the camera zooms into at the end, and an optional music track. No text overlays: the only type in the video is the page itself and the end logo.

Visual direction: Place the webpage flat on a clean studio floor (#f9fbfb center, #f2f3f6 corners), with 24px rounded corners and a soft shadow. The camera looks up the page while it travels down it, so the text reads upright and new sections come in at the bottom of the frame. About one element in three rises off the page as it comes into the frame: product windows, cards, charts, photos, quotes, logos and stat cells. Give each one its own height between 30 and 120px, and lift small elements less. The other elements stay flat. A raised element casts a soft, light shadow that is smaller than the element and sits a little lower on the page, so a band of the page shows between them. Use depth of field with the focus in the middle of the frame.

Timeline: 0–8.2s: one continuous glide from the hero headline to the footer. Start slow, speed up over 2s, then keep one speed. Tilt the camera down 40° at the start and 45° at the end. 7.75–9.25s: rise to look straight down on the whole page as one strip. Raised elements settle back onto the page. 9.25–9.47s: hold the full page with a slow push. 9.47–9.97s: dive into the hero. The hero lifts off as a floating card, and the rest of the page fades. 9.97–11.25s: the hero card holds alone with a slow push.

11.25–12.1s: zoom into the chosen shape of the logo mark in the page's nav bar. The shape travels on a straight line to the center of the frame while it grows (a fixed-point zoom in log space). The hero card fades around it.

12.2–13.1s: zoom out. The shape is now part of the centered end logo (about 84px high). The other parts of the mark come out of it one after the other (critically damped springs, 0.12s apart). The wordmark comes into focus from a blur.

13.1–14.5s: hold the logo with a slow 3% push that never stops.

Motion rules: No cuts, crossfades, sudden speed changes, sideways camera turns, zoom reversals or glow. Use a quarter-frame shutter for the motion blur. A half-frame shutter makes fast text look doubled.

Build: Use Playwright and Chromium at 1440px wide. Scroll to the end of the page first, so every scroll animation runs and the layout locks. Wait until any word cycle or counter shows its final state. Capture the page in 2000px tiles, because one full-page screenshot repeats the page after 16,384 device pixels. Capture the hero as a separate viewport screenshot at 2x, because full-page mode loses WebGL and canvas content. Save each element that can rise as its own 2x image, with its box in a JSON file. Then capture the page tiles again with those elements hidden, so


https://promptmotion.org/prompts


