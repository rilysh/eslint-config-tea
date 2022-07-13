## eslint-config-tea
A shareable eslint config for TypeScript which extends and prettify airbnb eslint config rules.

## Install
#### npm
```sh
npm install https://github.com/kiwimoe/eslint-config-tea.git
```
#### yarn
```sh
yarn add https://github.com/kiwimoe/eslint-config-tea.git
```
#### pnpm
```sh
pnpm install https://github.com/kiwimoe/eslint-config-tea.git
```
- Note: You may need to restart the eslint server after installation.

## Usage
```ts
// An example using undici fetch
import { fetch, type Response } from "undici";

(async () => {
    const data = await fetch("https://httpbin.org/post", {
        method: "POST",
        headers: {
            Accept: "application/json",
            "Accept-Language": "en-US",
            "Content-Type": "application/json",
        },
    }) as Response;
    const json = await data.json();
    console.log(json as string);
})();
```
