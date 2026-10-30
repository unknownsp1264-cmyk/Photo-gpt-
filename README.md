# PhotoEdit Studio

A responsive, browser-based portrait photo editor with:
- Automatic person segmentation and background blur (MediaPipe Selfie Segmentation, loaded from jsDelivr)
- Manual whole-image blur and soft overlay option
- Brightness, contrast, saturation controls
- HDR-style visual slider (not true multi-exposure HDR)
- AI-style Auto Enhance using local image brightness/contrast analysis
- Vivid, Warm, Cool, Black & White, Vintage, Cinematic, and Soft Portrait filters
- Original/edited comparison, reset, and PNG export

## Run locally
Open `index.html` in a modern browser with an internet connection. Automatic subject segmentation loads MediaPipe from a CDN. Basic editing and manual blur run in the browser.

## Publish on Netlify
1. Sign in to Netlify.
2. Choose **Add new site** → **Deploy manually**.
3. Extract this ZIP and upload the folder containing `index.html`.
4. Open the generated site URL.

## Notes
- Photos are processed in the browser; this project does not upload them to a server.
- Automatic subject detection works best with a clearly visible person and may need good lighting.
- Auto Enhance is a local smart adjustment, not a cloud generative-AI retouching service.
- HDR slider creates an HDR-style tonal effect; it does not reconstruct details from multiple exposures.
- Hair-edge masking and enhancement quality vary by image.
