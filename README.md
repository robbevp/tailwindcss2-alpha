This build will fail due to @tailwinddcss/ui in plugins.

```
yarn run tailwindcss index.css -o output.css
```

will produce

```
yarn run v1.22.5
$ /Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/.bin/tailwindcss build index.css -o output.css

   tailwindcss 2.0.0-alpha.1

   🚀 Building: index.css

   🚫 TypeError: value.charCodeAt is not a function
    at /Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/index.css:2:1
    at module.exports (/Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss-value-parser/lib/parse.js:17:20)
    at new ValueParser (/Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss-value-parser/lib/index.js:7:18)
    at ValueParser (/Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss-value-parser/lib/index.js:10:10)
    at transformValue (/Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss-functions/dist/lib/transformer.js:20:55)
    at /Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss-functions/dist/lib/transformer.js:72:24
    at /Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss-functions/dist/index.js:45:18
    at /Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss/lib/container.js:139:18
    at Rule.each (/Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss/lib/container.js:105:16)
    at Rule.walk (/Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss/lib/container.js:135:17)
    at /Users/robbevp/Documents/code/github-contributions/tailwindcss2-alpha/node_modules/postcss/lib/container.js:152:24

error Command failed with exit code 1.
```
