# Draw.io VS Code Integration

[![Twitter Follow](https://img.shields.io/twitter/follow/hediet_dev.svg?style=social)](https://twitter.com/intent/follow?screen_name=hediet_dev)

This unofficial extension integrates [Draw.io](https://app.diagrams.net/) (also known as [diagrams.net](https://www.diagrams.net/)) into VS Code, enabling seamless diagram creation and editing within your development environment.

## Features

- Edit .drawio, .dio, .drawio.svg or .drawio.png files in the Draw.io editor.
  - To create a new diagram, simply create an empty *.drawio, *.drawio.svg or *.drawio.png file and open it.
  - .drawio.svg are valid .svg files that can be embedded in Github readme files! No export needed.
  - .drawio.png are valid .png files! No export needed. You should use .svg though whenever possible - they look much better!
  - To convert between different formats, use the Draw.io: Convert To... command.
- Uses an offline version of Draw.io by default.
- Multiple Draw.io themes are available.
- Use Liveshare to collaboratively edit a diagram with others.
- Nodes/edges can be linked with code spans.

## About This Fork

This is a forked repository used for learning purposes and exploring VS Code extension development patterns. The original project can be found at the official Draw.io VS Code Integration repository.

## Demo

![Demo](./docs/demo.gif)

## Editing .drawio.svg/.drawio.png Files

You can directly edit and save .drawio.svg and .drawio.png files.
These files are perfectly valid svg/png-images that contain an embedded Draw.io diagram.
Whenever you edit such a file, the svg/png part of that file is kept up to date.
