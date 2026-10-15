# StudyOS

StudyOS is a static study portal for Network Security, Penetration Testing,
DevSecOps and Enterprise Management. The finished website and its documents
are in `dist/`.

## Publish with GitHub Pages

1. Create a GitHub repository and add the contents of this `master-study`
   folder to its root. Keep the `.github/workflows/deploy-pages.yml` workflow
   and the complete `dist/` folder.
2. In the repository, open **Settings → Pages** and set the build and
   deployment source to **GitHub Actions**.
3. Push to the `main` or `master` branch. The workflow deploys `dist/`;
   its URL will appear in the workflow run and in **Settings → Pages**.

The workflow can also be run manually from the repository's **Actions** tab.

On GitHub Free, GitHub Pages requires a public repository. Publishing this
site makes the study documents in `dist/documents/` publicly accessible, so
confirm that you have permission to share them before publishing. Keep the
repository root as this folder; do not upload the parent folder containing
other project files.
