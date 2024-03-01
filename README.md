## Nextjs for subpath
### includes
- NextJS `14.1.0`
- TRPC `10.45.1`
- React `18.2.0`
- Zod `3.22.4`
- @tanstack/react-query `4.36.1`
  
### config file `next.config.js`
```js
const config = {
  ...
  basePath: "/test-sub-path",
  ...
  env: {
    basePath: "/test-sub-path",
  }
};
```