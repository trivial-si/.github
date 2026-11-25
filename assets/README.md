# Brand assets

`trivial-superintelligence.png` is the original Trivial Superintelligence artwork supplied from the existing company branding. It remains the master reference.

## Current GitHub assets

- `trivial-logo-light.png`: navy lettering and orange dots on a transparent background, for light themes.
- `trivial-logo-dark.png`: light lettering and orange dots on a dark background, for dark themes.
- `trivial-avatar.png`: the existing wordmark on a navy square, with the small subtitle and tagline removed for legibility at avatar sizes.
- `trivial-avatar.jpg`: the same avatar encoded below GitHub's 1 MB upload limit.

The profile selects the appropriate logo using [GitHub's theme fragments](https://github.blog/changelog/2021-11-24-specify-theme-context-for-images-in-markdown/). The fragments are present on both the image and its link so the entire inactive variant is hidden. The organization avatar is a single image and deliberately carries its own contrasting background.

These presentation variants were edited with the built-in image generation tool from the existing company artwork. The JPEG is a size-compatible re-encoding. The original artwork is retained. The older `trivial-github-light.png` and `trivial-github-light.jpg` exports are superseded and are no longer used on the profile.

## Reproducing the logo edits

### Light-theme logo

Use case: background-extraction. Edit target: supplied original Trivial Superintelligence brand artwork. Create a clean, theme-ready light-mode presentation of this exact existing logo for a GitHub profile README. Preserve the original letter shapes, their spacing and proportions, the two orange dots over the i letters, and all three lines of text exactly: "trivial", "superintelligence", "It's not so trivial.". Make all lettering solid brand navy #152a40 and both dots solid brand orange #ff622e. Remove the large diffuse gray halo, glow, bevel and drop shadows so the mark remains crisp when reduced to 320px wide. Use a genuinely transparent alpha background, with no white or gray rectangle and no checkerboard baked into the image. Fit the full logo neatly into a wide 2:1 canvas with about 6% margins, keeping all text centered and fully inside. Do not substitute a new font, redesign the mark, add symbols, add text, or omit any of the three lines.

### Dark-theme logo

Input: the light-theme logo above.

Use case: precise-object-edit. Edit target: supplied clean Trivial Superintelligence logo. Produce its dark-mode companion for GitHub. Change every navy letter to warm white #f7f8f5, preserve both orange dots, and put the entire canvas on one perfectly uniform opaque dark GitHub background #0d1117. Preserve original exact letter shapes, letter spacing, text sizing, alignment, canvas dimensions and all wording: "trivial", "superintelligence", "It's not so trivial.". Three text lines, same layout as the input. Crisp solid flat lettering with smooth clean edges; no glow, halo, shadow, bevel, stroke, distressed texture or stray marks. The background outside AND between every letter must be exactly the same uniform #0d1117. This is a small technical palette adaptation of the existing brand, not a redesign.

### Organization avatar

Input: the light-theme logo above.

Use case: precise-object-edit. Edit target: supplied clean Trivial Superintelligence logo. Produce a compact square GitHub organization avatar using the existing "trivial" wordmark only. Keep its exact original letter shapes, spacing and two orange i-dots. Remove the two small lines below the wordmark for small-size readability. Recolor the letters to solid #f7f8f5, preserve the two dots in #ff622e, and use one opaque solid #152a40 navy background. Center the wordmark horizontally and vertically on a square canvas, occupying about 86% of the width with ample space around all edges. No glow, no shadows, no bevels, no texture, no gradients, no additional text, no replacement font and no new symbol. Crisp flat edges and strong contrast so the same single avatar is readable on both light and dark GitHub pages.
