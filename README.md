# puppeteer-base-project
https://medium.com/@jaredpotter1/connecting-puppeteer-to-existing-chrome-window-8a10828149e0

Simple base project showing puppeteer.

```
npm install

node index.js
```

Check the `puppeteer-us-keyboard-layout.ts` file for reference to all key definitions.

e.g.
`await page.keyboard.press("ArrowLeft");` where the string is a definition (the first column in the .ts file)
