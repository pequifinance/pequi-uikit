# 🟡 Pequi Finance UIkit

[![Version](https://img.shields.io/npm/v/@Pequi Finance-libs/uikit)](https://www.npmjs.com/package/@Pequi Finance-libs/uikit) [![Size](https://img.shields.io/bundlephobia/min/@Pequi Finance-libs/uikit)](https://www.npmjs.com/package/@Pequi Finance-libs/uikit)

Pequi Finance UIkit is a set of React components and hooks used to build pages on Pequi Finance's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @Pequi Finance-libs/uikit`

## Setup

### Theme

Before using Pequi Finance UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@Pequi Finance-libs/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@Pequi Finance-libs/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
