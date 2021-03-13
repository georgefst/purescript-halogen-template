# Develop
- `parcel dev/index.html --open`
- save file in IDE (or `spago build`), instantly updates webpage

# Deploy
- `mkdir prod && ln -s dev/index.html prod/index.html`
- `spago bundle-app -t prod/index.js`
- (e.g.) `cd prod && warp -p 8000`
