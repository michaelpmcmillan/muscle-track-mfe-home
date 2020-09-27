[![Netlify Status](https://api.netlify.com/api/v1/badges/c2cc3bc8-d934-40a7-a061-a909c9c1f6f5/deploy-status)](https://app.netlify.com/sites/muscle-track-home/deploys)

# muscle-track-mfe-navbar

Micro frontend homepage to be used with the main [container](https://github.com/michaelpmcmillan/muscle-track-mfe-container).

## Run in Development

```bash
yarn start:dev
```

## Notes

- Uses react-helmet to inject html headers, such as css cdn links. This keeps the micro-front-end self contained.
- Uses react-bootstrap and the bootstrap cdn.

## How was this app started?

```bash
npm install --global create-single-spa
npx create-single-spa
.
single-spa application / parcel
react
yarn
y (typescript)
michaelpmcmillan
muscle-track-mfe-home
```

