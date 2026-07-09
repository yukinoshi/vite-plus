# shim_npm_ignores_mismatched_package_manager

## `vp env exec node --version`

Ensure Node.js is installed first

```
<version>
```

## `npm --version`

npm shim ignores the mismatched pnpm@10.19.0 packageManager and uses the project Node's npm (not 10.19.0)

```
10.8.2
```

## `npx --version`

npx shim likewise ignores the mismatched packageManager (not 10.19.0)

```
10.8.2
```
