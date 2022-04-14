---
title: Homepage - Vortex Package Manager
description: Vortex is a fast package manager for Node.js, written in Rust.
---
# WIP: The fast package manager for Node.js
```sh
vortex install speed
```
ATM it's nothing impressive, just `init` and `run`
[GitHub](https://github.com/vortex-pkg/vortex)
## Current commands
`init`
| name | description | required |
|------|-------------|----------|
|N/A|

Creates a new package.json file. Atm it's basically just legacy `npm init` but better.

`run`
| name   | description                    | required |
|--------|--------------------------------|----------|
| script | The name of the script to run. | no       |

Runs a script in your package.json, if no script is give it lists all the scripts in your package.json file.
