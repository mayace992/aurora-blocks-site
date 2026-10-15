# Aurora Blocks public site

- Repository: mayace992/aurora-blocks-site; static GitHub Pages from main. This is separate from the mobile source repository aurora-blocks.
- Public root: https://mayace992.github.io/aurora-blocks-site/; support/ and privacy/ are store-facing contracts and must retain working URLs.
- index.html is the landing page, styles.css is shared by landing/support/privacy. No JavaScript runtime or package checks.
- 2026-10-15 requirement: show released iPhone/iPad/Android links and embed the PixelPicked badge for game59g3ipQMhDD. Badge verification is only complete when PixelPicked explicitly reports success; embedding alone is not acceptance.
- Tools: Serena currently points at another project and was not used for this repository. OpenSpec CLI is absent. Addressed HTML and links through rg/Git/HTML parsing; no tool installation or cross-project configuration was performed.
- Rollback: revert only the release-links/badge commit; keep store-facing support and privacy pages unchanged.
- Release evidence and marketing status are recorded in the parent workspace outputs/OCT7_RELEASE_STATUS.md; post-publication visual and PixelPicked acceptance checks remain OPEN until recorded there.
