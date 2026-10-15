# Osprey TDC Website

A lightweight, responsive, two-page static website for Osprey TDC Ltd, ready for GitHub Pages. No dependencies, tracking scripts, server, database, or external font requests.

## Pages
- `index.html` — homepage: consulting offer, approach, anonymised engagement experience, credentials, engagements and fees.
- `contact.html` — contact page with a `mailto:` button which opens the visitor's default configured email application to `lois@osprey-tdc.co.uk` (and adds a subject). A browser cannot force an unconfigured email app to open.

## Publish on GitHub Pages
1. Create a **public** GitHub repository, e.g. `osprey-tdc-website`.
2. Upload **all files from this directory directly to the repository root** (not the parent directory or the ZIP itself).
3. In the repository, go to **Settings → Pages**. Set source to **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. The included `CNAME` file sets the site’s canonical custom domain to `osprey-tdc.co.uk`. Confirm this under **Settings → Pages → Custom domain**.
5. Configure domain DNS at your provider (four GitHub Pages A records for `@`, plus `www` CNAME to `YOUR-GITHUB-USERNAME.github.io`). Do not remove unrelated DNS records, especially MX/TXT email records.
6. Once DNS is validated, enable **Enforce HTTPS** under GitHub Pages settings.

## Before publishing
- All client/employer names are omitted from the public site. Review achievement descriptions to ensure they are also appropriate for public sharing and comply with confidentiality terms.
- Verify the email mailbox `lois@osprey-tdc.co.uk` can receive email.
- Both site footers now identify Osprey TDC Ltd, registered in England & Wales, Company No. 16254009. **Before publishing, add the registered office address** to both footers (required UK company disclosure; not included here to avoid publishing a physical address without explicit confirmation).
- Confirm day-rate arrangement wording and SOW language are consistent with your actual business terms. No specific rate has been invented.
- If you later add analytics, cookies or a web contact form, you may need privacy/cookie information and any relevant consent mechanisms.

## Maintenance
Edit copy directly in HTML; change design tokens in `styles.css`. Commit updates to `main` to deploy automatically.
