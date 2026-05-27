# pagekind-privacy

Static GitHub Pages site at https://grifjef.github.io/pagekind-privacy/ — the public privacy policy for the [PageKind iOS app](https://github.com/grifjef/page-kind).

The canonical privacy wording lives in [`docs/privacy-promise.md`](https://github.com/grifjef/page-kind/blob/main/docs/privacy-promise.md) inside the app repo, and is also rendered in-app on the Settings → About → Privacy Promise screen, so the three renderings stay in sync.

## Updating

1. Update `docs/privacy-promise.md` in the `grifjef/page-kind` repo first.
2. Regenerate `index.html` here from the Markdown (manual or via the `pk-docs-sync` skill once it gains GH Pages support).
3. Commit + push — GitHub Pages picks up the change in ~1 min.

URL exists because the App Store Connect "Privacy Policy URL" field is required for submission.
