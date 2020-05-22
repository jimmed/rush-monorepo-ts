# TypeScript Monorepo Template

## Using the template

Rush must be installed globally.

1. [Create a new repository based on this template](https://github.com/jimmed/rush-monorepo-ts/generate)

2. Set the npm scope for your monorepo

   ```sh
   # Set the scope to '@myco'
   sed -i "s/@scope/@myco/" *.* **/*.*
   ```

   - [About npm scopes](https://docs.npmjs.com/about-scopes)

3. Update rush manifests

   ```sh
   rush update
   ```