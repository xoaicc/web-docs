# MD Quick Guide

This is a Short & Easy Guide for writing MD file. Help developers, who know markdown before can quickly start and easily remember with best practices.

## 1. Normal Typing

- # \# Heading 1
- ...
- ###### \#\#\#\#\#\# Heading 6
- \*\***Bold**\*\*
- \__Italic_\_
- \*\*\_**_Bold Italic_**\_\*\*
- \~\~~~Strikethrough~~\~\~
- \<sub><sub>Subscript</sub>\</sub>
- \<sup><sup>Superscript</sup>\</sup>
- > \> Blockquotes<br>\>\> Nested Blockquotes
- \`#RRGGBB`
- \`rgb(R,G,B)`
- \`hsl(H,S,L)`
- \- Unordered List
- 1\. Ordered List
- [x] \- [x] Complete Task List (can link to issues)
- [ ] \- [ ] Incomplete Task List (can link to issues)
- \[Link Title](Link)
- ![Image Alt](Image Link)
- @mentioning (username/team name if has read access or member of organization)
- \`\`\`[code_language]<br>Quoting Code<br>\`\`\`
- \```math<br>Full line Mathematical expression<br>\```
- \$\$Inline Mathematical expression$$
- :[EMOJICODE](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md):
- Footnote[\^1]<br>[\^1]: Reference
- \\\*Ignoring Markdown
- \<!-- Comments -->
- \> [!NOTE]<br>> Useful information that users should know, even when skimming content.
- \> [!TIP]<br>> Helpful advice for doing things better or more easily.
- \> [!IMPORTANT]<br>> Key information users need to know to achieve their goal.
- \> [!WARNING]<br>> Urgent info that needs immediate user attention to avoid problems.
- \> [!CAUTION]<br>> Advises about risks or negative outcomes of certain actions.

## 2. Data Structure

### 2.1. Folders

.
├── Parent Directory
│ ├── Child Directory
│ └── Final Child Directory
└── Final Parent Directory

### 2.2. Table

\| Left-aligned | Center-aligned | Right-aligned |
\| :- | :-: | -: |
\| Content Cell | Content Cell | Content Cell |

### 2.3. Collapsed Section

\<details>
\<summary>Collapsed Title\</summary>
Collapsed Content
\</details>
