# Flying Dragon Studio — website

Static website for Flying Dragon Studio (Couple Games support and legal information).

## Pages

- `/` — studio home
- `/support.html` — contact: flyingdragonsupport@gmail.com, app support and subscriptions
- `/privacy.html` — Couple Games Privacy Policy
- `/terms.html` — Couple Games Terms of Use

## Publish with GitHub Pages

1. Upload the website files to the `main` branch of `flyingdragonstudio/flyingdragonstudio.github.io`. Place files at the repository root, **not in a nested folder**.
2. Go to Repository Settings → Pages → Build and deployment.
3. Set Source to **Deploy from a branch**, branch **main**, folder **/(root)**; click Save.
4. Check `https://flyingdragonstudio.github.io/`, then open every linked page.

## Update app stores (only after the pages are live)

- Support URL: https://flyingdragonstudio.github.io/support.html
- Privacy Policy URL: https://flyingdragonstudio.github.io/privacy.html
- Terms URL: https://flyingdragonstudio.github.io/terms.html
- Standard Apple EULA: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/

The standard Apple EULA must also be included in the App Store product description for each localization where needed; this Terms page alone doesn't replace that requirement.

## Before release

Verify that the company name shown on this website and the actual owner/publisher named in both app stores reflect the business arrangement. A brand name is not necessarily the legal entity responsible for processing data. Confirm statements about analytics, subscriptions and SDK configuration still reflect the actual published builds. No form or server is included. All contact links are mailto links.

## Privacy & Security

All files are static, no external JavaScript, remote fonts or analytics. Never commit `.env` files, API keys, SDK credentials or private app source into this public repository.
