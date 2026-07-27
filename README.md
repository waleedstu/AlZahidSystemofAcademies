# Al-Zahid System of Academies — website proposal

Three static design directions. No build step, no dependencies, no backend.

## Structure

```
index.html      chooser page (links to all three)
logo.png        crest, white background removed
classic/        full-service school site (matches reference layout)
notice/         notice-board direction, for parents
genz/           bold direction, for ZIC students
.nojekyll       tells GitHub Pages to serve files as-is
```

## Deploy on GitHub Pages

1. Create a repo (public, for free Pages).
2. Push everything in this folder to the repo root.
3. Settings → Pages → Source: **Deploy from a branch** → `main` / `root`.
4. Live in ~60 seconds at `https://<user>.github.io/<repo>/`

## Custom domain

Add a file named `CNAME` at the root containing one line, e.g. `alzahid.pk`,
then point the domain's DNS at GitHub. Enable **Enforce HTTPS** in Settings → Pages.

## Notes before going live

- Photos in `classic/` and the gallery strips are labelled placeholders — swap for real campus photographs.
- Stats block (500+ / 40+ / 95% / 15+) and the two testimonials need the client's confirmation.
- Contact email in the footer is a Gmail address; move to one on the domain.
- All enquiry forms compose a WhatsApp message client-side. No server needed.
