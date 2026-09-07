# Shifting Lives — email assets

Images used by the Shifting Lives Accessibility result email (Google Apps Script).

They are served over jsDelivr's CDN and referenced by URL from the email template,
rather than embedded in the message. This keeps the email small and stops mail
clients showing them as attachments.

| File | Purpose | Source size | Rendered at |
|---|---|---|---|
| `sl-logo-header.png` | Header logo, cream/olive on Deep Forest `#123B2A` | 418x104 | 160x40 |
| `sl-logo-footer.png` | Footer logo, dark on light `#E3E7E5` | 450x111 | 126x31 |
| `sl-mail-icon.png` | Mail icon beside the support address | 72x72 | 18x18 |

Both logos are baked onto an opaque background on purpose: transparent PNGs get
their transparent areas recoloured by Gmail on mobile in dark mode.

This repo is public because jsDelivr can only serve public repositories.
