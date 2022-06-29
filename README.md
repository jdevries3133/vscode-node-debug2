# Node Debug; nvim compatibility fork

The newer vscode-node-debug debug adapter implementation is not strictly DAP
compliant, and [there isn't much interest in making it
be.](https://github.com/microsoft/vscode-js-debug/issues/969)

I don't expect it'll be possible to meaningfully maintain this project myself,
but vscode-node-debug is missing some features which are important to me, and
I am going to look into adding. There are also some failing tests on this
project as I write it now, and I might try to look into those too.

In any case, I'm not aware of any other forks that are actually being
maintained, and I'm happy to at least review PRs and try to keep this thing
alive, since it's currently the only node debugger that is compatible with
nvim-dap.

This extension is bundled with Visual Studio Code and together with **Node
Debug (legacy)** forms the [Node.js](https://nodejs.org) debugging experience.

**Node Debug** is the debugger for Node.js versions >= 8.0.

See a general overview of debugging in VS Code
[here](https://code.visualstudio.com/docs/editor/debugging).

Documentation for Node.js specific debugging can be found
[here](https://code.visualstudio.com/docs/nodejs/nodejs-debugging).

Please submit bugs and feature requests to the [VS Code
repository](https://github.com/microsoft/vscode/issues).


## License

Copyright (c) Microsoft Corporation. All rights reserved.

Licensed under the [MIT](LICENSE.txt) License.
