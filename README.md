# worker-test

This is a reproduction of the `SyntaxError: Cannot use import statement outside a module` issue

Steps:

1. Clone repo
2. Run `yarn/npm install` and `yarn/npm build`
3. Go into the /dist directory and use `npx http-server` to test.. you'll see that the *Hello There!* page renders correctly
4. Run `wrangler dev` or `wrangler preview` to see the error occur when visiting the page that wrangler serves
