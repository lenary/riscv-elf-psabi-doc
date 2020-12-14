RISC-V ROPI-RWPI psABI Addendum
===============================

v0.1

Introduction
------------

This document describes extensions and minor changes to the existing RISC-V ELF
psABI. The aim is to support position-independent code on embedded RISC-V
systems which are too simple to support a complex dynamic loader, and which
requires processes share a common address space. This document will also attempt
to explore the motivations behind and the implications of these extensions.
