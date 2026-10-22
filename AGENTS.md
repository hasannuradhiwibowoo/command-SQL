# Repository Guidelines

## Project Structure & Module Organization

This repository currently contains a single file, `command.txt`, with a brief note about Data Definition Language (DDL) commands. There are no source, test, or asset directories yet. Keep additions focused on command database documentation; if the project grows, group related material into clearly named folders and update this guide to match.

## Build, Test, and Development Commands

There is no build system or test suite configured. For now, edit the relevant text files directly and review changes with `git diff` when working in a Git checkout. Do not introduce build or test commands unless the project gains tooling that supports them.

## Coding Style & Naming Conventions

Use UTF-8 plain text or Markdown for reference material. Keep explanations short and practical, use consistent terminology, and include a small example when it makes a command easier to understand. Name new files descriptively, using lowercase words separated by hyphens (for example, `ddl-basics.md`).

## Testing Guidelines

No automated tests or coverage requirements are present. For documentation changes, check spelling, command syntax, and that examples accurately describe the intended database operation. Keep each entry readable in a plain-text editor.

## Commit & Pull Request Guidelines

Git history is not available in the current workspace, so no repository-specific commit convention can be confirmed. Use a concise imperative commit subject, such as `Document DDL commands`. Pull requests should summarize the material added or changed and include a sample command or excerpt when that helps reviewers assess correctness.

## Security & Configuration Tips

Do not add real credentials, connection strings, or production data to command examples. Use clearly fictional names and values.
