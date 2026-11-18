# ClipMaster AI v3 — local MP4 trimmer

## Run
Open `index.html` in a modern browser from a secure origin (for example, a GitHub Pages deployment). Some browsers may restrict ES modules when opened as a local file.

## What works
- YouTube URL validation and embedded preview only.
- Upload a video file from your device.
- Choose start/end seconds.
- Export the selected range as an MP4 using FFmpeg WebAssembly in the browser.
- No paid API or server-side video processing is used for this manual trimming feature.

## Limitations
- First use downloads FFmpeg WebAssembly files from jsDelivr and needs internet.
- Processing uses the phone's RAM/CPU. Long/high-resolution videos may fail or make the browser reload.
- This does NOT detect viral moments with AI, generate subtitles, or automatically create multiple highlights yet.
- A YouTube URL cannot be extracted by this app. Upload an original/authorized source file. Do not bypass YouTube restrictions or edit content without permission.
- Truly unlimited processing cannot be guaranteed on free infrastructure.
