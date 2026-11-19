# Self Manual · Explore What You Want to Study

[中文说明](README.md) · [Open the Chinese-language experience](https://yusheng266186-beep.github.io/self-manual/)

Self Manual is a reflective web experiment for students exploring degree programs. It asks about real experiences, choices, and interests, then turns the conversation into a personal notebook to guide further investigation.

## Five parts of the experience

1. Recall something you absorbed yourself in and describe what made it compelling.
2. Compare two real trade-offs and explain your preferences.
3. Use a historical figure's reflection card as a conversation prompt.
4. Add context about learning environments, difficulty, and practical constraints.
5. Read the synthesized notebook. Copy the text or save the report image, then use the suggested experiments and open questions to explore real courses and work.

The result is a starting point for exploration. Use current university materials, admission requirements, and concrete experiences to evaluate any program.

## Local preview and online features

The UI, styles, and conversation flow are in <code>index.html</code>. Serve the folder with <code>python3 -m http.server 8080</code>, then open <http://localhost:8080/>.

Conversation and report generation use an online model service. The browser saves the current conversation and report locally. Use fictional or non-identifying inputs when testing. A larger shared deployment should use a maintainer-controlled relay and documented limits. The project's Chinese README describes branch deployment and its maintenance checklist.
