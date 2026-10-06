---
name: Password-protected install icons
description: Deployment access protection can prevent unauthenticated manifest and icon fetching.
---

Keep the demonstration access wall in place when investigating installed-icon failures; do not make the deployment public as a workaround.

**Why:** The demonstration is intentionally access-restricted while an access agreement is being prepared. Unauthenticated production manifest and icon requests redirected to Replit's deployment access screen during investigation.

**How to apply:** Distinguish icon-file validation from an actual device install. Verify asset formats and links locally, but do not claim a protected production installation works without checking it in an authorised browser. Existing home-screen icons may remain cached.
