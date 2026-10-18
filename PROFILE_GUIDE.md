# Profile style and maintenance guide

The public introduction lives in [README.md](README.md). Lead with Ryan's technology risk direction, feature ROOK, then show selected public projects, technical foundations, education, and contact.

## Visual identity

ROOK: an architectural silver rook with a recessed violet core, faceted edges, and **Clarity. Control. Precision.** The crown represents control; the protected center represents evidence. Use the [standalone mark](assets/rook-mark.svg) for future approved brand applications.

| Role | Color |
| --- | --- |
| Charcoal background | `#111216` |
| Primary text | `#f1f1f5` |
| Silver text | `#c1c0cb` |
| Secondary text | `#aaa7b8` |
| Muted violet accent | `#a89ada` |
| Border | `#35343f` |

The static [desktop banner](assets/profile-banner.svg) and [mobile banner](assets/profile-banner-mobile.svg) have explicit backgrounds so their contrast remains stable in either GitHub theme. A GitHub-compatible `picture` element selects the compact composition at viewport widths of 600px or less. Native Markdown follows the reader's GitHub theme.

Use system fonts, local SVGs, meaningful alternative text, and one column. Keep essential information in text as well as the graphic. Avoid external font or image services, scripts, animation, badges, and layout tables. Preserve the existing account avatar.

## Content standards

- Keep career direction distinct from professional titles or experience already earned.
- Describe the dealership experience accurately; do not imply employment by Kia corporate.
- Distinguish completed work, coursework, learning exercises, and planned features.
- Keep ROOK's private status and synthetic local-demo limitations visible. Do not link readers to private repositories or copy private application source, documentation, or screenshots into this public repository without explicit approval.
- Describe independent code review as code review, not independent audit assurance or a security certification.
- Preserve the distinction between potential exceptions and findings, missing evidence and a pass, current status and historical timeliness, and automated results and human conclusions.
- Retain the AI-assistance disclosure without implying autonomous audit judgments.
- Present CISA examination preparation separately from certification earned.
- Preserve the verified LinkedIn URL and public project links. Do not add a public email address without the owner's direction.

## Before publishing an update

1. Check feature and verification claims against the current project records. Refresh status only when evidence supports it.
2. Verify relative images and links in GitHub's rendered README on the proposed branch.
3. Inspect light and dark themes and narrow mobile layouts; check image loading, text size, and horizontal overflow.
4. Confirm education, study status, experience, and project maturity remain accurate.
5. Use a focused pull request. The owner reviews and approves merging.

GitHub supports the `picture` element in Markdown: [GitHub image guidance](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github#adding-an-image).
