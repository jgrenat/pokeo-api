# Pokeo API

Based on the [PokeApi](https://github.com/PokeAPI), this project is used to deploy a static version of the data on surge for the JavaScript formation workshops at Viseo.

## Deployment

```sh
npm install
npm run deploy
```

(But as the [surge](https://surge.sh) account belongs to me, you have to be me to do that...)


## Deployed API 

By default, the API is hosted at [https://pokeo.surge.sh/api/v2/index.json](https://pokeo.surge.sh/api/v2/index.json).
The meta links won't work as is, you need to add `/index.json` at the end of the URLs.