<!-- lint ignore awesome-git-repo-age -->

<img src="https://github.com/nvim-neorg/neorg/raw/main/res/neorg.svg" align="right" width="144" />

# Awesome Neorg [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A collection of awesome Neorg notes, software and resources.

[Neorg](https://github.com/nvim-neorg/neorg) is an all-encompassing tool based around structured
note taking, project and task management, time tracking, slideshows, writing typeset documents and
much more.

## Contents

- [Parsers](#parsers)
- [Integrations](#integrations)
- [Neorg Modules](#neorg-modules)
- [Notes Collection](#notes-collection)
- [Resources](#resources)

## Parsers

- [norg-specs](https://github.com/nvim-neorg/norg-specs) - A collection of specifications and grammars for Neorg's file format, `norg`.
- [tree-sitter-norg](https://github.com/nvim-neorg/tree-sitter-norg) - A TreeSitter parser for the Neorg File Format.
- [tree-sitter-norg-meta](https://github.com/nvim-neorg/tree-sitter-norg-meta) - A TreeSitter parser for Neorg's `document.metadata` tag.
- [Norg.jl](https://github.com/Klafyvel/Norg.jl/) - A Julia parser for the Norg format.
- [norganic](https://github.com/Klafyvel/norganic/) - The solvent-free Norg compiler.
- [rust-norg](https://github.com/nvim-neorg/rust-norg) - A robust parser for Norg for tools that don't use tree-sitter.
- [minorg](https://github.com/pysan3/minorg) - MyNorg: `pandoc` to `norg` converter written in nim to import all *my* notes.
- [norgmill](https://github.com/hardfau1t/norgmill) - converts `.norg` files into html and serves files over http.

## Integrations
- [neorg-figlet-module](https://github.com/madskjeldgaard/neorg-figlet-module) - Figlet integration for Neorg
- [neorg-telescope](https://github.com/nvim-neorg/neorg-telescope) - Telescope.nvim integration for Neorg.
- [nixpkgs-neorg-overlay](https://github.com/nvim-neorg/nixpkgs-neorg-overlay) - Nixpkgs overlay that gives Nix users access to unstable versions of Neorg and its associated projects.
- [neorg-taskwarrior](https://github.com/skbolton/neorg-taskwarrior) - Taskwarrior integration into neorg.
- [neorg-fzflua](https://github.com/kev-cao/neorg-fzflua) - Fzf-lua integration for Neorg.
- [vite-plugin-norg](https://github.com/bottd/vite-plugin-norg) - Vite plugin for rendering `.norg` files in the browser

## Neorg Modules

- [Neorg Archive](https://github.com/bottd/neorg-archive) - Create and manage an archival workspace for your Neorg notes
- [Neorg Bookmarks](https://github.com/simonhughxyz/neorg-bookmark) - A bookmark manager the neorg way.
- [Neorg Capture](https://github.com/pritchett/neorg-capture) - A neorg module to capture quick notes using neorg-templates
- [Neorg colors](https://github.com/opipoy/neorg-colors) - a really simple module that allows you to change the colors of text
- [Neorg Conceal Wrap](https://github.com/benlubas/neorg-conceal-wrap) - Hard wrap text based on its concealed width, instead of its unconcealed width.
- [Neorg Contexts](https://github.com/max397574/neorg-contexts) - A neorg module that will display the headings you're currently inside at the top of the buffer.
- [Neorg Dew](https://github.com/setupyourskills/neorg-dew) - A Neorg modules ecosystem built around my personal note-taking workflow.
    - [Dew CatnGo](https://github.com/setupyourskills/dew-catngo) - Quick and simple note picker focused on category-based selection powered by [neorg-query](https://github.com/benlubas/neorg-query)
    - [Dew Crumb](https://github.com/setupyourskills/dew-crumb) - Displays breadcrumbs from headings in the winbar.
    - [Dew Decor Link](https://github.com/setupyourskills/dew-decorlink) - Inserts custom icons before Neorg link labels using a Telescope-powered picker
    - [Dew Highlights](https://github.com/setupyourskills/dew-highlights) - Custom Tree-sitter highlights in `.norg` files.
    - [Dew Random Quote](https://github.com/setupyourskills/dew-randomquote) - Inserts a randomly fetched quote into the current buffer
    - [Dew Smart Link](https://github.com/setupyourskills/dew-smartlink) - Automatically inserts a formatted link using the clipboard URL and fetched page title.
    - [Dew Transclude](https://github.com/setupyourskills/dew-transclude) - Automatically embeds the content of a linked note using a `!` prefix before internal links, and removes it when the prefix is deleted.
- [Neorg Exec](https://github.com/laher/neorg-exec) - code block execution for neorg.
- [Neorg Extras](https://github.com/juniorsundar/neorg-extras) - An neorg-agenda and neorg-roam add-on.
- [Neorg Hop Extras](https://github.com/phenax/neorg-hop-extras) - A neorg module that adds a few new types of links like commands, aliases, etc.
- [Neorg Interim LS](https://github.com/benlubas/neorg-interim-ls) - Provide refactoring functionality through neovim's LSP interface. Serves as a completion source, and can complete categories (when used with `neorg-se`).
- [Neorg Jupyter](https://github.com/tamton-aquib/neorg-jupyter) - A neorg module to work with jupyter notebooks inside neorg.
- [Neorg Kanban](https://github.com/max397574/neorg-kanban) - A neorg module that will allow you to display your gtd tasks in kanban-like floating windows.
- [Neorg SE](https://github.com/benlubas/neorg-se) - The power of a search engine for your Neorg workspace. Search notes, titles, categories, and more.
- [Neorg Templates](https://github.com/pysan3/neorg-templates) - A neorg module to create templates for norg file with dynamic values via LuaSnip.
- [Neorg Worklog](https://github.com/bottd/neorg-worklog) - A neorg module that logs the files you work on in your daily journal.

## Notes Collection

- [Library of Norgxandria](https://github.com/nvim-neorg/library-of-norgxandria) - This repository aims to be a monolithic collection of notes about any topic, written in the `.norg` file format.

## Resources

- [Norg Tutorial](https://github.com/pysan3/Norg-Tutorial) - Norg tutorial with kickstart configuration.
- [From No Org to Neorg](https://www.youtube.com/playlist?list=PLx2ksyallYzVI8CN1JMXhEf62j2AijeDa) - Youtube video series from the author.

### Developer Resources

- [Neorg Module Tutorial](https://github.com/benlubas/neorg-module-tutorial) - Written tutorial that goes over the basics of the modules system, and how to create a new core/external module.
- [Extending Neorg](https://www.youtube.com/playlist?list=PLxpY86LRR3B0rtOBjXAsq1XnsOt4m4owu) - Youtube video series to build custom modules.
