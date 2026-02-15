# The Rust Programming Language — Learning Progress

This repository contains my code as I go through "The Book" (The Rust Programming Language). It includes exercise solutions, theoretical snippets, and final projects from the chapters.

The repository is structured as a **Cargo Workspace**, allowing all sub-projects to share a single build directory to save disk space and improve compilation speed.

## Structure

- **projects/** — Standalone projects developed throughout the book (e.g., Guessing Game, Minigrep, Web Server).
- **chapters/** — Small code snippets and theory-based examples categorized by chapter.

## Usage

Since this is a workspace, you should run commands from the root directory using the `-p` (package) flag.

**Run a specific project:**

```bash
cargo run -p guessing_game
```

**Run tests for the entire workspace:**

```bash
cargo test
```

**Build all projects:**

```bash
cargo build
```

## Resources

- [The Rust Programming Language](https://doc.rust-lang.org/book/)
