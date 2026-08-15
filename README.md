# qlguard

> **Status: idea — not yet implemented.** This repository stakes out the concept; there is no code to install yet.
Compile-time safety for run-time queries. Stop finding ColumnNotFound errors in production.

A pain point in Python's dynamic nature: treating SQL as opaque strings leads to runtime errors that could be caught earlier. Inspired by Rust's sqlx, which does compile-time validation, this adapts the concept to Python's ecosystem with a CLI/library approach.
