Works
```
pnpm add -w @nyarthan/pnpm-plugin-acme
```

Does not work
```
pnpm add --config @nyarthan/pnpm-plugin-acme
```
Error:
```
 ERR_PNPM_FETCH_401  GET https://npm.pkg.github.com/@nyarthan%2Fpnpm-plugin-acme: Unauthorized - 401

No authorization header was set for the request.

These authorization settings were found:
@jsr:registry=https://npm.jsr.io/
//registry.npmjs.org/:_authToken=npm_[hidden]
@nyarthan:registry=https://npm.pkg.github.com/
//npm.pkg.github.com/:_authToken=ghp_[hidden]
Installing config dependencies...
 ERR_PNPM_FETCH_404  GET https://npm.pkg.github.com/@nyarthan/pnpm-plugin-acme/-/pnpm-plugin-acme-1.0.0.tgz: Not Found - 404

An authorization header was used: Bearer ghp_[hidden]
```
