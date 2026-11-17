# School Index – Plans to Progress

District-led school improvement reviews: from each school's commitments to implementation evidence, scholar outcomes, and district follow-through.

**Live site:** https://melatkins2-ops.github.io/grps-school-index-plans-to-progress/

## What's here

- `index.html`: the tool, including the school list (each school's designation, commitment, and source plan link)
- `images/`: GRPS logo

## Good to know

- Working prototype, not an official system of record. Source plans are linked individually.
- Reviews are saved in the browser (local storage). Use **Backup data** and **Import reviews** to move them between devices.
- A school whose plan work has not started (for example, a newly identified TSI school) shows without a commitment statement until the plan exists.

## Updating the site

Edit the files on a branch and open a pull request. GitHub Pages publishes `main` automatically, usually within a minute or two of a merge.

## Automated site check

Every pull request and every push to `main` runs **Site check** (`.github/workflows/site-check.yml`). It opens the site in a headless browser at desktop (1366px) and phone (390px) widths and fails if the page throws a JavaScript error, a local file or image is missing, or the page scrolls sideways. See the Actions tab for results.

Maintained by GRPS Community & Student Affairs.
