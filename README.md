# vimma-updates

Signed update manifests for [Vimma](https://github.com/vimma-browser/vimma), served at
`https://updates.vimma.dev` by a Cloudflare Worker that deploys every push to `main`.

Each manifest is written and signed by Vimma's `update-publish.yml` workflow when a release is
published; nothing here is edited by hand. Vimma accepts a manifest only if it is signed by a key
pinned in the browser. How the keys are kept and how to verify a manifest:
[docs/runbook.md](https://github.com/vimma-browser/vimma/blob/main/docs/runbook.md) ("Update
signing keys and the update host") and
[docs/security.md](https://github.com/vimma-browser/vimma/blob/main/docs/security.md).
