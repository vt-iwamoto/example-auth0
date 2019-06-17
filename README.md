# nuxt-auth0

> A simple example that shows how to use [Nuxt.js](https://nuxtjs.org) with [Auth0](https://auth0.com)

![nuxt-auth0](https://cloud.githubusercontent.com/assets/904724/22703834/d971838c-ed65-11e6-90f9-5ecf2a1be5f0.gif)

You can access a simple demo here: https://auth0.nuxtjs.org

## Credits

This example is inspired by [next.js-auth0](https://github.com/luisrudge/next.js-auth0) made by [Luís Rudge](https://github.com/luisrudge).

## Setup

* Create an account at Auth0 (https://auth0.com)
* Add your endpoints to your client's allowed urls like this ![nuxt-callbacks](https://user-images.githubusercontent.com/31644329/59735104-20d02000-928f-11e9-88df-d782ad2101b2.png)

* Copy the file `config.sample.json` at the root folder, rename it as `config.json` and add your Auth0 keys

## Running Locally

```
git clone https://github.com/nuxt/example-auth0.git
cd example-auth0
npm install
npm run dev
```

## Running with Docker

```
git clone https://github.com/vt-iwamoto/nuxt-example-auth0.git
cd nuxt-example-auth0
sh exec.sh
```
