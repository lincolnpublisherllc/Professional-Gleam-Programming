Professional Gleam Programming — Extracted Code

This README explains how the chapter-by-chapter code archive is organized and how to use it.

Summary

Chapters: 15

Code blocks: 268

Total lines of code detected: 809

Generated on: 2025-09-17 23:41 (Africa/Lagos)

Folder structure

Each chapter has its own folder. Inside you will find files named code_###.* in the order they appeared in the book.

extracted_code/
  Chapter_01/
    code_001.gleam
    code_002.sh
    code_003.toml
    ...
  Chapter_02/
    code_001.gleam
    code_002.gleam
    ...
  ...

File types

File extensions are inferred from content:

.gleam for Gleam source

.sh for shell commands and terminal lines

.toml for gleam.toml and config fragments

.yml for CI or workflow examples

.sql for SQL examples

.json for JSON snippets

.txt when the type is unclear but still looks like code

How the extraction worked

A simple set of rules picked out code-like lines such as Gleam keywords, braces, commands, and config keys. When a non-code line appeared, the current block ended. This keeps related lines together but may split long examples into a few files. If you want me to merge blocks or adjust what counts as code, say the word and I’ll regenerate.

Per-chapter summary
Chapter_01

Blocks: …, Lines: …

code_001.gleam (… lines)

code_002.sh (… lines)

code_003.toml (… lines)

Chapter_02

Blocks: …, Lines: …

code_001.gleam (… lines)

code_002.gleam (… lines)

(I kept the list short here to stay readable. The saved README includes a per-chapter count and sample filenames. If you want the full index of every file listed out, I can generate that in this message too.)

Tips

If you plan to run the Gleam files, copy them into a Gleam project and add any missing imports.

Shell scripts may include single-line commands. Review them before running.

Config fragments likely need to be pasted into an existing file rather than run as is.

Known limitations

Some prose lines that contain symbols like : or {} might be misclassified as code.

Multi-line examples that include text in between can be split into several blocks.

If you spot anything off, tell me the chapter and a short description. I’ll fix the rules and rebuild.
