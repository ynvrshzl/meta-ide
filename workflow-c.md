# Conceptual workflow of how this product/instrument would actually benefit the human systems engineer.

> Program starts...
- Homepage, splash screen, recent activity, feed? [^3]
- Press button, or Open command palette, or terminal command: "Open folder as schematic"
- Program scans "~/folder" for files, configuration "~/.meta" and project files.
- Constructs internal database of code (Like an AST but human useable, like SQL)

> Once the program has loaded the local codebase...
- Nothing should be displayed yet. Perhaps an overview of the project with documentation, or a standard application-wide homepage.

> Tools at this stage...
- Suggested actions should appear at this stage, almost like "context-aware prompts" but without AI. E.g., "Inspect system density (overload), Review documentation, etc."
  This opens the possibility of "points" as in https://brilliant.org providing an interactive learning experience, whilst constructing systems [^5]
- Terminus (integrated terminal) provides all of the system commands.
- Command pallete, a graphical version of the terminus. For common actions "Create new main module" or "Enter query mode"

[^3]: Volatile "feed" dynamic systems, use with care!
[^5]: We should definitely explore this idea.
