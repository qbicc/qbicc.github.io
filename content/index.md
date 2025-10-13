---
title: Qbicc Home
description: An experimental pure-Java program analysis and compilation toolkit.
name: Qbicc
simple-name: Qbicc
image: qbicc_logo_horizontal_default.svg
social-twitter:
social-facebook:
social-github: qbicc/qbicc
social-linkedin: 
layout: default
---

# About qbicc

[qbicc](https://github.com/qbicc/qbicc) is an experimental native image compiler for Java with the following features:

 * Cross-compilation - the host OS and CPU are not required to match the target's OS and CPU
 * Pure Java - does not require any specific JVM distribution to be used or installed, and no JNI is required
 * Support for native compilation using Maven
 * Clean architecture - supports multiple backends and optimizations by way of plugins
 * No JDK needs to be installed on the target (running) system

## Requirements

qbicc runs on any JVM, as long as it is Java 17 or later. The host system must have a working compiler toolchain (C compiler and linker), as well as an LLVM installation for the LLVM backend.

## Get started

Get started by reading [the README file](https://github.com/qbicc/qbicc#readme) on GitHub.

## Interact with the developers

Join [the developer Zulip chat](https://qbicc.zulipchat.com) to ask questions, offer ideas or contributions, or observe the development process.

To report an issue, use [the GitHub issue tracker](https://github.com/qbicc/qbicc/issues).