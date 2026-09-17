# Leonardo Sivieri

Software engineer based in Brescia, Italy. I build web applications end to end - API design, data modelling, and the interfaces that sit on top of them.

Currently at **OneAM**, working on Symfony products and the internal bundles they share: console tooling, file handling, reusable domain pieces. The framework isn't the interesting part - the constraint is. Code that several products depend on has to stay small, documented, and hard to misuse, and every shortcut you take in a shared bundle is a shortcut you take in all of them at once.

Studying Computer Engineering at **Università degli Studi di Brescia**.

## How I work

- **Static analysis as a gate, not a suggestion.** PHPStan and a formatter run before anything is committed, so review time goes to design instead of style.
- **Types all the way through.** Typed PHP on the backend, TypeScript on the frontend, and no `any` smuggled across the boundary between them.
- **Read the existing patterns first.** A codebase with one mediocre pattern used consistently beats one with three good patterns used at random.
- **Delete before you generalise.** Premature abstraction is harder to undo than duplication.

## Agentic tooling

I run Claude Code as a configured system rather than a chat window. Conventions live in a checked-in `CLAUDE.md`; subagents are scoped to narrow jobs instead of being general assistants — reviewing generated Doctrine migrations for destructive or unrelated queries, checking new code against framework conventions, mapping an unfamiliar feature from route to template before I touch it. Hooks close the loop: static analysis and the formatter have to pass before a session can end, and a guard refuses to let the agent touch git history at all.

The point isn't speed. It's that the failure modes of an agent are predictable, so they can be fenced off with tooling instead of supervision.

## Tools I reach for

`PHP` · `Laravel` · `Symfony` · `Doctrine` · `TypeScript` · `Vue` · `Java` · `MySQL` · `Docker` · `Vite`

Comfortable picking up whatever a problem actually needs - the list above is where I've spent the most hours, not a boundary.

## Upstream

- [microsoft/vscode#336540](https://github.com/microsoft/vscode/issues/336540) - proposed an API for `TreeItem.command` to declare an alternative command on modifier-click, closing an asymmetry with the existing `menus` contribution point.

## Elsewhere

- LinkedIn: [leonardosivieri](https://www.linkedin.com/in/leonardo-sivieri/)
- Email: [sivieri.leonardo@gmail.com](mailto:sivieri.leonardo@gmail.com)
