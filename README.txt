SPANISH AGENT ADVENTURE — VERSION 3.0

UPDATING GITHUB PAGES
1. Extract this ZIP.
2. Upload all extracted files and folders to the ROOT of your GitHub Pages repository, preserving images/defaults and images/custom.
3. Commit the files. Open the published site in Safari on your iPad.
4. Close and reopen the installed Home Screen app after publishing. Version 3.0 appears under the app title.
5. If an old version persists, in Safari clear website data for the published site, then reopen it. Note that clearing site data may reset saved progress.

AUDIO ON IPAD
- Use Safari or the Home Screen installed app, and tap Hear Spanish, Hear sentence, or the large word image.
- Increase media volume, disconnect Bluetooth speakers if necessary, and check silent/audio routing.
- iOS speech synthesis depends on installed system voices; Settings > Accessibility > Spoken Content > Voices > Spanish may help.
- The app displays audio status. Speech works through the device's built-in speech synthesis; it is not bundled audio files.
- If no Spanish voice is available, iOS may use its default voice. Real iPad testing is still required.

IMAGES
- The image inventory XLSX is the reference for the exact filenames.
- Add custom JPGs to images/custom/ without renaming the defaults. Example: img_m1_1.jpg.
- The app uses the custom JPG when available and the default SVG otherwise.
- Do not upload images without appropriate rights; track licensing in the workbook.

WHAT CHANGED
- Fixed malformed click handlers that could break Spanish audio buttons.
- Tap large mission picture to speak the Spanish word.
- Tap quiz picture to select the answer; quiz score and immediate spoken correction.
- Reduced sizes and overflow for iPad and iPhone.
- Updated offline service-worker cache to v3.

LIMITATIONS
- Audio requires supported iOS speech synthesis and device voice settings.
- No native iPad or iPhone hardware testing has been performed in this environment.
- The default SVGs use emoji rendered by the device, not original bespoke illustrations.
