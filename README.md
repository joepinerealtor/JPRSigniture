# JPRSigniture

Public image hosting and HTML starter files for Gmail email signatures.

## Templates

- `signature.html` - close recreation of the personal signature layout with headshot, contact details, social icons, and meeting button.
- `signature-hybrid.html` - combines the personal signature with Keller Williams Leading Edge branding, a red vertical divider, and a bottom tagline area inspired by the work signature.

## Recommended setup

1. Upload signature images into the `assets/` folder.
2. Go to **Settings > Pages** in this repository.
3. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Save.
5. After GitHub Pages publishes, image URLs will look like:

```text
https://joepinerealtor.github.io/JPRSigniture/assets/headshot.png
```

Template URLs will look like:

```text
https://joepinerealtor.github.io/JPRSigniture/signature.html
https://joepinerealtor.github.io/JPRSigniture/signature-hybrid.html
```

## Gmail notes

Keep important contact details as real text instead of image-only content. Some email clients block images by default, so text ensures the signature still works when images do not load.

For best Gmail compatibility, copy the rendered signature from the browser page and paste it into Gmail's signature editor.
