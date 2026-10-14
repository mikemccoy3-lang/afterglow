# Afterglow

Personal Prequel-style photo editor. One file (`index.html`), no install, no subscription, no watermark.

**Use it:** double-click `index.html` (opens in your browser), then Open or drag in a photo.
Pick a Look, set Intensity, tweak Effects/Adjust, press-and-hold the photo (or Space) to compare, Export.

- 15 built-in looks: Kodak Gold, Portra, Fuji 400H, Cinematic, Moody Garage, Chrome Pop, Golden Hour,
  Dreamy, Light Leak, Dusty 70s, Noir, VHS, Y2K Digicam, Glitch
- Effects: split toning, film grain (size), dust & scratches, halation, vignette, glow, light leak
  (color + angle), RGB split, VHS lines, retro date stamp
- Adjust: exposure, contrast, highlights, shadows, fade, saturation, vibrance, warmth, tint, sharpen/soften
- "Save as my look" stores your own presets in this browser
- Export renders at full resolution (up to 6000px long edge) as JPEG; on iPhone it opens the share sheet

Everything runs on the GPU (WebGL) locally; photos never leave the device.
Dev: `index.html?src=path/to/photo.jpg` auto-loads a same-origin image for testing.
