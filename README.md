# sanity-block-content-to-react-types

Started after reading this issue https://github.com/sanity-io/block-content-to-react/issues/26

Create a folder `@types` in the root of your TS project.

Add `block-content-to-react.d.ts` to it.
In your `tsconfig.json`:
```json
"files": [
  "@types/block-content-to-react.d.ts"
],
```
When/if this gets better, I can try to move this to [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped)


Pull Requests, suggestions are welcome!
