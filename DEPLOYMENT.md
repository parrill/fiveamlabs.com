# Deployment

Static GitHub Pages placeholder. The only visible body text is `fiveamlabs.com`. No build step or external assets. Local browser verification passed through http://127.0.0.1:8766/fiveamlabs.com/.

Published to parrill/fiveamlabs.com; Pages build passed and live HTTP body verified as only fiveamlabs.com. Restarted certificate provisioning by removing/re-adding the custom domain. GitHub reports certificate approved for apex and www, expires 2027-02-08, with https_enforced=true. Live TLS and HTTP redirect still propagating at last check.

HTTPS: GitHub Pages obtains a free Let's Encrypt certificate automatically after domain/DNS validation. For stalled provisioning, remove and re-add the custom domain in Pages settings, then enable Enforce HTTPS when available.

Research DNS currently points to Squarespace. Planned DNS after Pages is configured: replace parking apex A records with 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; set www CNAME to parrill.github.io. Preserve unrelated mail/TXT records. DNS changes have not been applied; Squarespace login access is required.
