# Ovibos public pages

Static Support and Privacy Policy pages for the separate public GitHub Pages repository `luddite478/ovibos-pages`.

Expected URLs after Pages is active:

- Support: `https://luddite478.github.io/ovibos-pages/`
- Privacy policy: `https://luddite478.github.io/ovibos-pages/privacy.html`

Only the files in this directory belong in the public repository. Do not publish app source, benchmark photos, credentials, or private results with it. The pages use no scripts, third-party fonts, or analytics.

## Release review before App Store submission

- Replace the pre-release notice and check every purchase, refund, balance, and reinstall statement against the implemented app and backend.
- Confirm the production OpenAI project settings, data sharing opt-in status, and provider retention wording.
- Set and verify retention for installation/request records, completed results, purchase records, backups, and CloudWatch logs. The current AWS credentials could not read the CloudWatch log-retention setting.
- Confirm the support email is monitored and the data-deletion workflow can locate and verify a requester without an app account.
- Confirm the public URLs work without sign-in and update App Store Connect and the in-app Privacy link if the URLs change.
