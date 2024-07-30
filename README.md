# Pixi ❤️ WASM

[Visit the deployed example](https://wolfv.github.io/pixi-wasm/)

This is an example of how to use pixi with WebAssembly (thanks to [emscripten-forge](https://emscripten-forge.org)).

Pixi is a conda-compatible package manager written in Rust. It uses the `pixi.toml` to define everything that goes into the environment, including tasks, dependencies, and more.

It uses `jupyterlite` under the hood to bundle and serve a WASM environment that is created with pixi!

## Usage

```bash
pixi run start
```

To run the example locally.

The deployment is made by the Github action (that pushes to an artifact): [deploy.yml](.github/workflows/deploy.yml).
Note that you need to change the Github setting in order to use an "artifact" as deployment (and not the `gh-pages` branch).

## Read more

You can read more about this in our blog post: [Pixi ❤️ WASM](https://prefix.dev/blog/pixi_wasm).