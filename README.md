# Fuse

The FuseCode Launcher

## Installation

(Come back in a few days!)

## Usage

`fuse <app-name> [args]`

* If `<app-name>` isn't supplied, it will download and launch the system UI plugin and dependencies.

## What is this?

This is the FuseCode runtime launcher and CLI.

It's job is to provide dynamic code download services with dependency resolution and code (re)loading.

Currently the downloader supports Maven and Git sources.  Transitive dependency resolution is only supported for Maven dependencies.  Plugins for FuseCode itself are implemented using Git.

Git-based dependencies support automatic dynamic code reloading whenever source code is changed.

Java compilation isn't supported yet.  Maybe using http://dcevm.github.io/ in the future.
