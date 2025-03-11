## A Full Live-Scripted CAD Kernel and IDE in the Browser.

Use code to create 3D Models with features ranging from simple primitives + CSG to complex revolves, sweeps, and fillets.  Cascade Studio exposes the full power of the [OpenCascade](https://github.com/Open-Cascade-SAS/OCCT) kernel, while providing a concise standard library for simple operations.

Save your completed models to .step, .stl. or .obj, or copy the url and share it with the community.

## Features
 - A Powerful Standard Library to Simplify Model Construction
 - Intellisense Autocomplete/AutoSuggest and Documentation
 - Access to the Full OpenCASCADE Kernel (via the `oc.` namespace)
 - Automatic Caching Acceleration of Standard Library Operations
 - `.STEP`/`.IGES`/`.STL` Import - `.STEP`/`.STL`/`.OBJ` Export
 - URL Serialization of code for easy sharing and ownership
 - Save/Load Projects to preserve Code, Layout, and Imported Files
 - Integrated GUI System for Simple Customization
 - Easily Installable for Offline-use as a Progressive Web App
 - **Free and Open Source under the MIT License**

## Contributing

Cascade Studio is entirely static assets and vanilla javascript, so running it locally is as simple as running a server from the root directory (such as the [VS Code Live Server](https://github.com/ritwickdey/vscode-live-server), [Python live-server](https://pypi.org/project/live-server/), or [Node live-server](https://www.npmjs.com/package/live-server) ).

Pull Requests to this repo are automatically hosted to Vercel instances, so other users will be able to test and benefit from your modifications as soon as the PR is submitted.

## How to run


Just open the folder and run:

'''bash
python3 -m http.server 8080
'''
