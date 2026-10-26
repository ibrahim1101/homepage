# Ibrahim Homepage — Cloudflare Pages

All website files are in dist/.

Cloudflare Pages settings: production branch main; build command exit 0; build output directory dist; root directory left blank. Connect this repository using Git integration.

Add ibrahimshaik.com and www.ibrahimshaik.com under the Pages project custom domains after checking existing root and www DNS records. Do not alter unrelated subdomain or email records.

The contact form sends requests to https://services.ibrahimshaik.com/api/personal-contact. It requires the Studio worker deployment and the existing Turnstile widget to allow ibrahimshaik.com. A pages.dev preview hostname is not currently allowed for form delivery. The mailto link remains available. No secret API keys are in this package.

Personal shortcuts stay in local browser storage on the current domain and browser; they are not access control and do not transfer from the preview to the new domain.
