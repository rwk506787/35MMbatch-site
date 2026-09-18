# 35mm Retro site

This is the public static support site for 35mm Batch, becoming 35mm Retro in
version 1.2, subject to App Store approval. The current published version is
35mm Batch 1.1, with Golden, Silver and Evergreen. Instant, framing and
original-size reversible Photos edits are upcoming 1.2 features, not current
1.1 features.

It contains:

- `index.html` — app landing page
- `privacy.html` — privacy policy
- `support.html` — support contact and troubleshooting details
- `terms.html` — brief terms page linking to Apple’s Standard EULA
- `404.html` — GitHub Pages fallback page

The site has no JavaScript or third-party runtime dependencies. It is intended
to be served from GitHub Pages at:

<https://rwk506787.github.io/35MMbatch-site/>

## Deployment

GitHub Pages publishes the root (`/`) of the `main` branch. A push or merge to
`main` automatically starts GitHub's generated `pages-build-deployment`
workflow and publishes the site; there is no separate manual deploy step or
checked-in workflow file. Do not merge to `main` just to stage or preview a
change. Pushing `app-store-identity-refresh` updates PR #2, not the live site.

Keep the pre-release wording until version 1.2 is approved **and available to
download** on the App Store. Approval alone, a development install or a
TestFlight build is not public availability. Before then, name version 1.1
and its three looks as the current offer, and label the rename, Instant,
framing and original-size Photos edits as coming in 1.2, subject to App Store
approval, including in search/social metadata and support instructions.

After confirming public availability, update those version labels and the
download wording in a follow-up PR. Preserve the approved hero headline,
existing URLs, email address, images, pricing/access rules and legal
commitments. After an approved merge, check the Pages workflow result and the
live landing, support, privacy, terms and nested-404 links.
