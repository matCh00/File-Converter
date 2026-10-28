# Third-party notices — FILE CONVERTER

This site downloads and republishes the engine assets from the public project:
- Project: https://github.com/Skitionek/serverless-office-converter
- Engine: LibreOffice compiled to WebAssembly; upstream documents LibreOffice 26.8.3 in `office-converter/lo/manifest.json`. LibreOffice is distributed under the Mozilla Public License 2.0 (MPL-2.0): https://www.mozilla.org/MPL/2.0/
- Vendored `office-converter/vendor/xz-decompress.min.js`: xz-decompress 0.2.3, MIT (xz-embedded public domain; walloc MIT), as documented by upstream in `office-converter/vendor/README.md`.

The GitHub Actions workflow copies these upstream assets at deployment time. Please consult the linked upstream repository and license notices for the exact source version and any additional notices packaged with each release.
