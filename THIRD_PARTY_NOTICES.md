# Third-party notices

MP3 encoding uses **lamejs 1.2.1** by Alexander S. Bokovikov and the LAME project contributors.

- Source package: https://www.npmjs.com/package/lamejs/v/1.2.1
- Project: https://github.com/zhuker/lamejs
- License: LGPL-3.0; see `vendor/lamejs/LICENSE` and `vendor/lamejs/src/main/java/COPYING`.
- Unmodified corresponding source is included as `vendor/lamejs/lamejs-1.2.1.tgz`.
- `gas/Encoder.html` embeds the original minified build, followed by our worker message handler. `tools/build.cjs` regenerates that file.
- No external CDN is contacted when using the app.
