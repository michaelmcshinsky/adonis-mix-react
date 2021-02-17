# Adonis-React + Tailwind
A monorepo combining AdonisJS with ReactJS via the npm package [adonis-mix-react](https://github.com/wahyubucil/adonis-mix-asset#readme).

Article detailing step by step creation is covered [here on Dev.to](https://dev.to/mmcshinsky/build-a-fullstack-app-with-adonis-and-react-1m50).

## Features
1. AdonisJS
2. ReactJS
3. Laravel Mix (adonis-mix-asset)

## Installation

```
git clone https://github.com/michaelmcshinsky/adonis-mix-react.git
cd adonis-mix-react
cp .env.example .env
node ace generate:key
yarn install
```

## Usage

### Development
```
yarn dev
```
Navigation to [http://localhost:3333](http://localhost:3333)

### Production
```
yarn build
yarn start
```

### Documentation

* [AdonisJS](https://preview.adonisjs.com/guides/quick-start)
* [ReactJS](https://reactjs.org/docs/getting-started.html)

## TODO

- [ ] Update Hot reloading when fixable
