```
> yarn
> yarn build
yarn run v1.3.2
warning package.json: No license field
$ babel index.js
TypeError: Cannot read property 'node' of undefined
    at PluginPass.AssignmentExpression (<dir>/node_modules/@babel/plugin-proposal-decorators/lib/index.js:139:224)
    at newFn (<dir>/node_modules/@babel/traverse/lib/visitors.js:223:21)
    at NodePath._call (<dir>/node_modules/@babel/traverse/lib/path/context.js:64:19)
    at NodePath.call (<dir>/node_modules/@babel/traverse/lib/path/context.js:38:17)
    at NodePath.visit (<dir>/node_modules/@babel/traverse/lib/path/context.js:99:12)
    at TraversalContext.visitQueue (<dir>/node_modules/@babel/traverse/lib/context.js:139:18)
    at TraversalContext.visitSingle (<dir>/node_modules/@babel/traverse/lib/context.js:98:19)
    at TraversalContext.visit (<dir>/node_modules/@babel/traverse/lib/context.js:180:19)
    at Function.traverse.node (<dir>/node_modules/@babel/traverse/lib/index.js:76:17)
    at NodePath.visit (<dir>/node_modules/@babel/traverse/lib/path/context.js:106:18)
error Command failed with exit code 1.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.
```
