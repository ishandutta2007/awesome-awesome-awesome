# Contribution Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

---

## The Pull Request Checklist

Before submitting a PR, make sure all of the following are true:

- [ ] I've read the [awesome manifesto](awesome.md) and my list complies
- [ ] The entry I'm adding is relevant to one of the existing sections or warrants a new section
- [ ] The entry has a **URL** linking directly to the project or resource
- [ ] The description explains **why** it belongs here, not just **what** it is
- [ ] The description is **one sentence**, ending in a period, starting after ` — `
- [ ] The entry is in **alphabetical order** within its section (when practical)
- [ ] The URL is **alive** — I've verified it resolves
- [ ] My PR title is `Add [Entry Name]` (for new entries) or `Update [Section]` (for changes)

---

## Adding an Entry

### Format

```markdown
- [Project Name](https://url.example.com) — One sentence that explains why this belongs here and what value it provides to the reader.
```

Not:

```markdown
- [Project Name](https://url.example.com) — A project that does X.  ← Too vague
- [Project Name](https://url.example.com) — This is a tool for Y.   ← Starts with "This"
```

### Quality bar

This list is **curated**, not exhaustive. To be included, an entry should:

- Be **actively maintained** (last commit or release within 2 years, or be a canonical reference)
- Have **real-world adoption** in research, industry, or the open-source community
- Be **genuinely useful** to practitioners in its domain — not just tangentially related
- For datasets: be **publicly accessible** and have meaningful scale or quality
- For papers: be a **landmark or foundational** work, or a recent breakthrough

### Adding a new section

A new section is warranted when:

- There are at least **5 quality entries** that don't fit existing sections
- The domain has clear **relevance to future technologies** (coming decades, not legacy)
- The entries are meaningfully **distinct** from existing sections

Open an issue first to discuss new sections before submitting a PR.

---

## What Does Not Belong

- Web development tools (JS frameworks, CSS libraries, REST API design)
- Legacy technologies with no forward trajectory
- Paid/proprietary tools with no open API or community edition (with rare exceptions for best-in-class)
- Personal projects without meaningful external adoption
- Anything that requires a closed waitlist to access
- Promotional content or self-promotion without clear merit

---

## Updating an Existing Entry

If a URL changes, a project was renamed, or a description is outdated, please open a PR with the fix. Use the PR title `Fix [Entry Name]` or `Update [Entry Name]`.

---

## Removing an Entry

Entries may be removed if:

- The project is **abandoned** (no updates for 3+ years, no maintainer response to issues)
- The URL is **permanently dead** and no mirror exists
- The project was deprecated in favor of a clearly better successor (link to the successor)

Open an issue to propose removal with evidence before submitting a PR.

---

## Reporting Issues

- **Dead link?** Open an issue with `[dead link]` in the title
- **Missing important project?** Open an issue with `[suggestion]` in the title
- **Wrong section?** Open an issue with `[wrong section]` in the title

---

## License

By contributing, you agree your contributions will be licensed under the [CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0).
