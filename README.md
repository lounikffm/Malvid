# Malvid

[![Travis Build Status](https://travis-ci.org/comwrap/Malvid.svg?branch=master)](https://travis-ci.org/comwrap/Malvid) [![AppVeyor Status](https://ci.appveyor.com/api/projects/status/6fxwnrdhoh7xw9n1?svg=true)](https://ci.appveyor.com/project/electerious/malvid) [![Coverage Status](https://coveralls.io/repos/github/comwrap/Malvid/badge.svg?branch=master)](https://coveralls.io/github/comwrap/Malvid?branch=master)  [![Dependencies](https://david-dm.org/comwrap/Malvid.svg)](https://david-dm.org/comwrap/Malvid#info=dependencies)

UI to help you build and document web components.

![Malvid UI in a browser](https://l.electerious.com/uploads/big/e6cb112abd2afd7aafeb210074dfeb2a.png)

## Contents

- 🏃 [Get started](#get-started)
- 📄 [Introduction](#introduction)
- 🔗 [Links](#links)
- ⚙️ [Documentation](#documentation)

## Get started

Malvid can be integrated into your project in two ways: Using the CLI *or* using the API.

## Introduction

### What is Malvid?

Malvid helps you to build, document and visualise components by turning a directory into an interactive UI.

### How does it work?

1. You execute Malvid using the CLI *or* using the API
2. Malvid scans the folder you've specified and generates a static HTML output
3. You open the output in your browser to start browsing through your components

### Why Malvid?

- It visualises components in a way that improves how your team works with components
- It doesn't force you to use a defined directory structure, templating language or build tool
- It integrates perfectly with [Rosid](https://rosid.electerious.com)
- It's built on popular modules like [React](https://reactjs.org)
- It's lightweight and only includes what it really needs

### What are components?

Components are independent and reusable pieces of a project. A component could be a tiny chunk of HTML, a whole page or something in between. Malvid does not enforce any specific templating engine or naming conversation for those components.

## Links

Boilerplates:

- 📐 [Skeleton Components](https://github.com/electerious/Skeleton-Components): UI for components written in Nunjucks, JS (with Babel, UglifyJS) and SASS (with cssnano, Autoprefixer)

Guides:

- 📄 [Sharing components between front-end and back-end](https://medium.com/@electerious/sharing-components-between-front-end-and-back-end-1e9a624bceae)

Similar tools:

- 🛠 [Fractal](https://fractal.build)
- 🛠 [Pattern Lab](http://patternlab.io)

## Documentation

### Requirements

Malvid depends on...

- [Node.js](https://nodejs.org/en/) (v8.9.0 or newer)
- [npm](https://www.npmjs.com)

Make sure to install and update all dependencies before you setup Malvid.