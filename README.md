# NxVueTest

After upgrading from `16.2.2` to `16.3.2` the `nx-vue` plugin throws this error:

```
 >  NX   Failed to process the project graph with "nx-vue".

   Cannot read properties of undefined (reading 'some')
   
   Because of the error the Nx daemon process has exited. The next Nx command is going to restart the daemon process.
   If the error persists, please run "nx reset".

error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```

## Repro Steps

1. clone, install
2. run `yarn nx format:write`
3. observe error

