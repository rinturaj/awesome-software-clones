# Contributing to Awesome Software Clones

Thank you for considering contributing to **Awesome Software Clones**!

This repository aims to be a community-driven catalog of commercial software and their open-source alternatives.

---

## Guidelines for Inclusion

When proposing an addition or update, please verify that your suggestion meets the following criteria:

1. **Commercial Target**:
   - The commercial product should be well-known, widely used proprietary software or SaaS.

2. **Open-Source License**:
   - The alternative must be truly open-source (under an [OSI-approved](https://opensource.org/licenses) or Free Software license such as MIT, Apache 2.0, GPL, AGPL, BSD, etc.).
   - Source-available software with restrictive non-compete clauses or proprietary commercial locks should be noted carefully or avoided.

3. **Publicly Accessible & Actively Maintained**:
   - The source code must be hosted in a public repository (e.g., GitHub, GitLab, Codeberg).
   - The project should show recent maintenance or stability (active commit history, responsive issue tracker).

4. **Scope & Accuracy (Complete vs. Partial Replacements)**:
   - We welcome both **complete replacements** (feature-for-feature alternatives) and **partial alternatives** (tools covering a specific core capability of the commercial product).
   - Ensure the alternative legitimately satisfies the core use case of the commercial software it is listed against.

5. **No Duplicates & Alphabetical Order**:
   - Search the list before submitting to prevent duplicate listings.
   - Place entries logically within the most appropriate existing category.

---

## Submission Format

All entries in `README.md` follow a Markdown table format:

```markdown
| Commercial Software | Open-source Alternative |
|---|---|
| Commercial Product Name | [Alternative Name](https://official-link-or-repo/) |
| Commercial Product Name | [Alternative 1](url), [Alternative 2](url) |
```

- Link to either the official project homepage or the primary open-source Git repository.
- Multiple high-quality alternatives can be listed for a single commercial product, separated by commas.
- Avoid tracking parameters or affiliate links in URLs.

---

## How to Submit a Pull Request

1. **Fork** the repository to your own GitHub account.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/awesome-software-clones.git
   cd awesome-software-clones
   ```
3. **Create a topic branch**:
   ```bash
   git checkout -b add-alternative-name
   ```
4. **Edit `README.md`**:
   - Add your entry to the appropriate category table.
   - Keep markdown clean and valid.
5. **Commit your changes**:
   ```bash
   git commit -m "Add <Alternative Name> as alternative to <Commercial Product>"
   ```
6. **Push to your fork**:
   ```bash
   git push origin add-alternative-name
   ```
7. **Open a Pull Request**:
   - Provide a brief description of the project and why it is a viable alternative.
   - Mention whether it is a full or partial alternative.

---

## Code of Conduct

Please note that this project is released with a Contributor [Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

