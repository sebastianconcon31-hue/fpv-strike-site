# FPV Strike site (draft, local)

Goal: the website and privacy-policy links Meta's Details tab asks for (App metadata > Details: Website, Privacy Policy).
Status 2026-10-07: pages written, NOT published. Contact email on both pages: sebastianconcon31@gmail.com (his choice, 2026-10-07).
Facts in privacy.html come from the native build: no HTTP code in `native/scripts` (`grep HTTPRequest` finds nothing), Android internet permission is on only for Meta's entitlement check (`scripts/store/entitlement.gd`), settings are in `user://settings.cfg`.
Next: pick the email, publish (GitHub Pages from a small public repo under his account, or Cloudflare Pages), paste the two URLs in the dashboard.
