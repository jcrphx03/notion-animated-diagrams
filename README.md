# Notion Animated Diagrams

Animated HTML diagrams for the DSC (Dsmart Cloud) Notion workspace, hosted free with GitHub Pages.

Each diagram is one self-contained HTML file. GitHub Pages serves it at a public link, and the link is embedded in Notion (Wiki pages, project pages, dashboards). The same files can later be used on the DSC website and exported to MP4 for LinkedIn and other social media.

## Live site

Index of all diagrams: https://jcrphx03.github.io/notion-animated-diagrams/

| Diagram | File | Live link |
| --- | --- | --- |
| DSC Project Onboarding Workflow | `DSC-Onboarding-Workflow.html` | https://jcrphx03.github.io/notion-animated-diagrams/DSC-Onboarding-Workflow.html |
| DSC Agent Factory | `agent-factory.html` | https://jcrphx03.github.io/notion-animated-diagrams/agent-factory.html |
| Animated examples | `animated-examples.html` | https://jcrphx03.github.io/notion-animated-diagrams/animated-examples.html |

## How to add a new diagram

1. Save the diagram as one `.html` file (all CSS and SVG inside the file).
2. Name it with words joined by hyphens, for example `dsc-audit-cycle.html`. Links are case-sensitive.
3. Add the file to the root of this repo and commit to `main`.
4. Add a link to it in `index.html` and a row to the table above.
5. Wait 1–2 minutes. The live link is `https://jcrphx03.github.io/notion-animated-diagrams/<file-name>.html`.

## How to show a diagram in Notion

1. Open the Notion page.
2. Type `/embed` → Enter → paste the live link → **Embed link**.
3. Under the embed, add one line: file name and date.

For an MP4 version (LinkedIn, slides, Notion `/video`), see Wiki page **09 · Process — Animated diagram to MP4, GitHub Pages and Wiki**.

## Rules

- **Public repo.** Anyone with the link can see these files. Never add client data, prices, credentials or private notes.
- **One file per diagram.** The HTML file is the master copy. MP4s are exports made from it.
- **Changes are logged** in the commit message (what changed and why).

## Related

- DSC Notion workspace project: P-008 - Notion New Implementations (repo `p-008-notion-new-implementations`).
