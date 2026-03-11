# Stratified Media Sampler

Long-form audio and video sampler for quickly capturing the overall impression of a work by playing short randomized segments across the full timeline.

All processing happens locally in the browser. Files are not uploaded.

## Features

- Load multiple media files or drop a folder containing media files
- Treat multiple files as one continuous timeline
- Build randomized segment lists using stratified sampling
- Use presets or custom values for layer count and segment length
- Optionally keep each segment within a single file
- Reproduce a run with the same file order, settings, and seed
- Review the playback log and copy it as JSON
- Switch the UI between Japanese and English

## Usage

1. Open the app in a modern desktop browser.
2. Add files by drag and drop or by using the file picker.
3. Review or reorder the input file list if needed.
4. Choose a preset or set custom sampling values.
5. Generate the segment list.
6. Start playback and move through segments with the playback controls.

## Browser Notes

- Chrome, Edge, and Firefox are expected to work.
- Folder drag and drop behavior differs slightly across browsers.
- If folder drag and drop is unreliable, use regular file drag and drop or the file picker.

## Reproducibility

Reproducibility depends on all of the following:

- the file order
- the sampling settings
- the seed value

## Development

The main application file is `stratified-media-sampler.html`.

For GitHub Pages, `index.html` redirects to that file.

