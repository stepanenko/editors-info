# Neovim

## Vim vs Neovim - Main Differences

## Overview

-   **Vim**: Mature, stable, minimal text editor.
-   **Neovim**: Modern fork of Vim with improved architecture and
    extensibility.

------------------------------------------------------------------------

## Key Differences

### 1. Architecture & Extensibility

-   Vim uses Vimscript for plugins.
-   Neovim supports Lua and external plugins (Python, JS, etc.).
-   Neovim is easier to extend and configure.

### 2. Built-in LSP

-   Vim requires plugins for Language Server Protocol.
-   Neovim has built-in LSP support.

### 3. Async Performance

-   Vim has limited async capabilities.
-   Neovim is designed with async support from the start.

### 4. UI Flexibility

-   Vim is mostly terminal-based.
-   Neovim supports modern UI features (floating windows, GUIs).

### 5. Configuration

-   Vim uses vimrc (Vimscript).
-   Neovim uses init.lua (Lua), which is faster and cleaner.

### 6. Ecosystem

-   Vim is stable but slower in innovation.
-   Neovim has more active development and modern plugins.

------------------------------------------------------------------------

## When to Choose

### Choose Vim if:

-   You want stability and minimal setup.
-   You already have an existing config.

### Choose Neovim if:

-   You want modern development features.
-   You plan to use LSP, Treesitter, and advanced plugins.
-   You prefer Lua over Vimscript.

------------------------------------------------------------------------

## Summary

Neovim keeps the Vim philosophy but modernizes the experience, making it
the preferred choice for most developers today.
