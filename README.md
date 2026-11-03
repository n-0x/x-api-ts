# x-api-ts

Generated from [n-0x/x-api](https://github.com/n-0x/x-api); do not edit generated code.
The package `@n-0x/x-api-ts` contains JavaScript modules and TypeScript declarations
under `n0x/` and depends on `@bufbuild/protobuf` 2.16.0.

`sync.yml` polls every 15 minutes. To regenerate a specific source tag, run:

```sh
gh workflow run sync.yml -R n-0x/x-api-ts -f tag=vX.Y.Z
```

The workflow sets the package version from the tag, typechecks and commits the
client on `main`, then publishes the same tag. Existing tags are left unchanged.
Consumers depend on `github:n-0x/x-api-ts#vX.Y.Z` and never generate code themselves.
