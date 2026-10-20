# Athena

VILT's Redmine theme, for Redmine 7. Loads core's stylesheet and changes only
what is listed below. Licence: doc/LICENSE. Fonts: Inter and Manrope, SIL OFL
(doc/OFL-*.txt).

## Changes to core

**Fonts**
- Body text: Inter. Headings: Manrope. Both self-hosted.

**Top bar**
- Background `#1f212b`, links `#636678`, white on hover, no hover background.
- Link spacing 20px, weight 500, letter spacing 0.1em.

**Header**
- Background `#2b2e3a`, min height 90px.
- Athena logo before the title. Title uppercase, letter spacing 0.1em.
- Search and project jump box stacked, 200px wide.

**Navbar** (main menu)
- Background `#363945`, height 48px.
- Items `#bcc0d4`, white on hover, weight 500, letter spacing 0.1em.
- Open item: white background, link-coloured text, no marker line.

**Links**
- `#50566d`, weight 500. Hover `#e90062`.

**Buttons and checkboxes**
- Submit buttons `#e90062` with white text, `#2b2e3a` on hover, `#caccce` when
  disabled.
- Checkboxes `#e90062`.

**Icons**
- Link icons `#1f212b` instead of blue. Status icons (ok, error, warning,
  checked) unchanged.

**Issue page**
- Issue box background `#fef9e9`.

**Issue lists** (project and global issue lists, My page blocks)
- Row background by priority: Urgent `#ee8fb7`, High `#f1c9da`, Low `#e0e5fa`.
  Normal unchanged.
- Text black on High and Urgent, bold on Urgent.
- Hover: `#363945` with white text instead of yellow.

**All lists**
- Selected rows: `#363945` instead of blue.

**Other**
- Current-item marker (`--color-current-marker`, e.g. admin sidebar) `#e90062`.
- Login panel `#e2e2e2`. SSO button (redmine_oauth) text black.
- Current page in pagination `#e90062`.
- Admin sidebar: no background on the current item.
- Dropdowns, autocomplete, date picker: link colour instead of blue.
- Mobile: header `#363945`, flyout menu `#2b2e3a`.
- Favicon.
