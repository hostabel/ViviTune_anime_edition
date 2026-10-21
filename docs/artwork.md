# Sakura artwork

`src/ViviTune/Assets/sakura-mascot.png` is an original decorative illustration generated for this fork with the built-in OpenAI ImageGen tool on 2026-10-21. It is bundled locally as an Avalonia resource; the application makes no network request to load it. The illustration does not change connection state or intercept input.

Generation prompt:

> Use case: stylized-concept. Asset: original mascot illustration for ViviTune desktop app, Sakura anime edition. Draw one friendly adult anime woman, long flowing lavender hair fading to pink, bright violet eyes, small sakura flower hair clip, large futuristic pink headphones, tasteful fully clothed cream and plum techwear jacket with a rose ribbon, holding one hand up in a little wave. Elegant Japanese anime key visual, crisp polished linework and soft cel shading, small sparkles and a few cherry blossom petals. Waist-up portrait, entire head and hair and shoulders inside frame with generous margins, vertical composition. Palette: blush pink, lilac, cream, deep plum. No text, no logo, no watermark, no extra people. Transparent background, clean alpha cutout. Friendly calm expression; designed to sit on a dark plum software interface.

The screenshots in README are rendered by `ViviTune.Shots` from the actual Avalonia interface with demo connection data; they are not generated UI mockups.

`src/ViviTune/Assets/icon.svg` is the editable vector source for the sakura/V application and tray icon. `icon.ico` contains PNG frames at 16, 24, 32, 48, 64, 128 and 256 pixels.

## Traffic-based outfits

The adult character Vivi (25) has two additional original variants, edited from `sakura-mascot.png` with built-in ImageGen on 2026-10-21. Both are bundled Avalonia resources with transparent backgrounds.

- `src/ViviTune/Assets/sakura-casual.png`: without the outer jacket, displayed from 1 GiB of measured session proxy traffic.
- `src/ViviTune/Assets/sakura-summer.png`: opaque one-piece swimsuit, displayed from 10 GiB.

Casual edit prompt:

> Edit the provided original fictional anime mascot into an alternate everyday outfit. The character is Vivi, an adult woman age 25. Preserve her exact face, adult proportions, lavender-pink hair, violet eyes, headphones, sakura hair clip, gentle expression, waving hand, pose, camera angle, framing and illustration style. Remove only her large cream outer jacket, revealing a tasteful opaque plum sleeveless high-neck top and the same skirt beneath, with the pink ribbon and small blossom decoration. Modest casual summer fashion; neutral non-suggestive presentation, no lingerie, no nudity. Keep the entire same silhouette placement and canvas proportions for swapping in a software sidebar. Transparent alpha background, no text or new props.

Summer edit prompt:

> Create an alternate summer swimsuit outfit for this original fictional anime mascot, Vivi, an adult woman aged 25. Preserve exact face, adult proportions, violet eyes, lavender-pink hairstyle, sakura hair clip, headphones, small friendly smile, waving hand, same pose, framing, canvas proportions and polished anime art style from the reference. Replace the jacket, top and skirt with a tasteful opaque one-piece athletic swimsuit, plum with pale pink side panels, a high rounded neckline, regular full-coverage bottom and tiny sakura flower emblem. Ordinary swimwear fashion illustration, relaxed non-suggestive posture, no erotic emphasis, no nudity, no transparent fabric, no lingerie. Keep character scale and head position the same for swapping artwork in a desktop app. Transparent alpha background, no text, no extra props.
