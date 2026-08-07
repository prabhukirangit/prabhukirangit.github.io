# prabhukirangit.github.io

Personal homepage, served by GitHub Pages at <https://prabhukirangit.github.io>.

A single self-contained `index.html` — no build step, no dependencies, no
framework. Edit the file, commit, push; Pages redeploys in under a minute.

| File | Purpose |
|---|---|
| `index.html` | The whole site. Inline CSS/JS, light + dark themes, responsive. |
| `okts-preprint.pdf` | Current OKTS preprint, linked from the Research section. Refresh with the copy command below whenever the paper is rebuilt. |

## Refresh the preprint

```bash
cd ../OKTS && python paper/make_results.py && cd paper && make pdf
cp main.pdf ../../prabhukirangit.github.io/okts-preprint.pdf
```

## Open items

- [x] ORCID [0009-0001-9971-9589](https://orcid.org/0009-0001-9971-9589) linked
      in the header and in the page's JSON-LD.
- [ ] Add the arXiv ID to the Research and Publications sections once the
      preprint is announced.
