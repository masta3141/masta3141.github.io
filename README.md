# masta3141.github.io

Root of the GitHub Pages domain. It only exists for:

- `.well-known/assetlinks.json` — Digital Asset Links that verify the Android app
  `io.github.masta3141.hsktrainer` (HSK Trainer, a Trusted Web Activity) for this domain,
  so the app runs without a browser address bar. Add the Play App Signing fingerprint
  from the Play Console next to the upload key fingerprint.
- `index.html` — redirects to the app at [/chinese-trainer/](https://masta3141.github.io/chinese-trainer/).

`.nojekyll` is required, otherwise GitHub Pages does not publish the `.well-known` folder.
