# WIP: SDF Viewer

A fast and cross-platform Signed Distance Function (SDF) viewer, easily integrated with your SDF library.
The main objetive of this app is to quickly visualize new SDFs while designing them.

## Features / future plans

- [x] Cross-platform: desktop (Linux, Windows, MacOS) and web.
    - MacOS is not tested but should work.
    - TODO: mobile support needs a little more work.
- [ ] Cross-language: easy to integrate with most languages and frameworks.
- [x] Very-fast initialization on all platforms.
- [x] Interactive framerate (uses the GPU for viewing the SDF).
- [x] Different rendering materials (color, metallic, roughness...).
- [x] Surface parameters to quickly customize from the UI.
- [ ] Upload your SDF to a server and display it anywhere with a link.
- [ ] Render/export a triangle mesh built using different algorithms.

## Demo

**[Try it online!](https://yeicor.github.io/sdf-viewer/)** The native version is recommended for better
performance.

This example and then renders an SDF at 60 FPS on an integrated graphics card (i7-9750H). The initial progressive load
of the SDF is also interactive at 30 FPS (configurable).

![demo.gif](.github/docs/demo.gif)

## Building

All [releases](https://github.com/Yeicor/sdf-viewer/releases) include builds for most platforms.

Follow the [release.yml](.github/workflows/release.yml) workflow to learn how to build the project by yourself.

