# Shelver Change Log

## Purpose

This file tracks meaningful product, UI, and stability changes to Shelver over time.

## Recent Changes

### Brand and Visual Refresh

- Shifted the product umbrella language toward `Shelf University`
- Refreshed parts of the home screen visual system
- Improved card styling, shelf styling, and overlay polish
- Refined stage transition and result overlay presentation
- Improved certificate and academy header presentation

### Stability and UX Fixes

- Fixed repeated scoring on already-solved shelves
- Scoped free-play hint highlighting to the correct shelf
- Adjusted result overlay heading spacing to avoid clipped descenders

### Brand Consistency Pass

- Updated home branding copy to use `Shelf University`
- Updated academy card descriptions and badge text
- Updated certificate copy to align with current naming
- Fixed `Non Fiction Academy` to `Nonfiction Academy`

### 2026-04-10

- Enabled the `Daily Challenge` home card and updated its home copy to reflect the new format.
- Changed the daily shelf from 5 books to 8 books with one check attempt per day.
- Added `Done` and `Attempted` badge states using `shelver-daily-{date}` localStorage values.
- Added daily-only lock helpers so the shelf, hints, undo, settings, and reroll controls are disabled after the challenge starts or ends.
- Added a Daily Challenge completion/attempted overlay that sends the player back home with a clearer `come back tomorrow` loop.

## Suggested Format For Future Entries

### YYYY-MM-DD

- short summary of the change
- user-facing effect
- any important implementation note

## Notes

- Keep entries concise.
- Prefer user-facing outcomes over file-by-file notes.
- Include logic changes, bug fixes, and visible design changes.
