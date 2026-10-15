# Resume link page

Static one-pager served at https://shinegun.github.io/resume/

- `index.html` - the resume link page (no build step, plain HTML/CSS)
- `Muhammad-Aqil-Nazri-Resume.pdf` - the resume the QR points at
- `resume-preview.jpg` - page 1 rendered at 2x, shown on the page

Update flow: replace the PDF (keep the filename), re-render the preview, commit, push.
The QR image itself lives outside this repo, at `~/resumes/Aqil-QR-resume.{png,svg}`.
