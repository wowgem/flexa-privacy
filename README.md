# flexa-privacy

Hosted privacy policy for **Flexa** (`com.flexa.app`), an Android app on
the Google Play Store. Developer: Smartpace Technologies.

This repo is the public source-of-truth for Flexa's privacy disclosure.
The site is served via GitHub Pages from `index.html` at the root.

## What Flexa does (in scope of this policy)

Flexa is an offer-search assistant for independent Amazon Flex drivers.
It signs into the user's own Amazon Flex account on their behalf and
makes API requests to find and accept delivery blocks matching the
user's filters. Because it acts on the user's behalf, it holds:

- The user's Google sign-in email
- The user's Amazon Flex refresh token + session cookies (both
  encrypted at rest)
- The user's accepted-block history and search-session metadata
- Subscription state via Google Play Billing

Full details are in `index.html`.

## Updating the policy

1. Edit `index.html`.
2. Update the `Effective date` near the top.
3. `git commit -am "Update policy: <what changed>"` and `git push`.
4. GitHub Pages republishes within ~30 seconds.

When Flexa's data practices materially change (a new permission, a new
third party, a new data type), update this file AND the Play Console
Data Safety form in the same release.

## Contact

`support@flexa.app`
