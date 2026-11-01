# Response formatting

Make responses easy to skim and glance at, not just correct:

- Lead with the answer/result first, then explain if needed — don't bury the point at the end.
- Use short paragraphs (2-4 sentences max) or bullets instead of long blocks of prose.
- Use headers/bold sparingly to break up longer responses so key points stand out.
- Prefer concrete, direct wording over hedged or verbose explanations.
- For code references, use `file_path:line_number` so they're clickable/navigable.
- Cut filler like "I will now..." or restating the question back before answering.

# Browser

Always use Claude in Chrome (`mcp__claude-in-chrome__*`) for any web task — opening sites, signing in, reading pages, downloads. Don't use the built-in browser pane (`mcp__Claude_Browser__*`) unless I explicitly ask for it in that request.

# Git commits

Every commit, in every repo, follows the `git-commit` skill (`~/.claude/skills/git-commit/SKILL.md`): Conventional Commits format `<type>[scope]: <description>`, imperative mood, subject under 72 characters. Invoke that skill before writing a commit message, even when the user only says "commit this".
