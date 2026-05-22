# Fantasy/RPG English Vocabulary

Many English learners can read everyday English, but fantasy and RPG texts still feel difficult.

The problem is not words like *and*, *bread*, or *boy*.

The problem is words like *hallowed*, *profane*, *defiled*, *sundered*, *attuned*, *withered*, *oathbound*, *wyrm*, *relic*, *sigil*, and *covenant*.

This repository provides curated fantasy/RPG English vocabulary lists for that exact gap.

It is designed for players and readers who already know basic English, but struggle with fantasy-register words used in quests, items, lore, dialogue, magic, religion, war, ruins, dragons, undead, oaths, nobility, and worldbuilding.

The dictionaries are language-neutral and can be used by learners with any native language.

## Start Here: Readable Workbook

The easiest way to use this vocabulary is:

```text
wow_vocab_core_readable.xlsx
```

This workbook is designed for Excel, LibreOffice, OpenOffice, and similar office suites.

It is usually more convenient than CSV files because the columns are already ordered, filters are enabled, and the first columns are meant for reading:

```text
word
forms
meaning
frequency
```

Technical metadata appears to the right.

### Recommended Study Workflow

1. Open `wow_vocab_core_readable.xlsx`.

2. Go to the `Lemma Large` sheet.

3. Start from the top and study words by frequency.

4. Mark words you already know in green (or delete it).

5. Mark words you did not know, or want to review later, in yellow.

6. Periodically return to the yellow words and review them again.

This workflow works well because `Lemma Large` groups forms together.

For example, instead of studying three separate rows:

```text
add
added
adds
```

you study one lemma row:

```text
word: add
forms: add;adds;added
frequency: 117
```

You can also filter by category, review flag, or confidence if you want a more focused session.

Suggested color meaning:

- green - I know this word
- yellow - I did not know this word or want to review it
- no color - not reviewed yet

## What Is Inside

The repository contains public derived vocabulary dictionaries built from World of Warcraft retail language data.

### Core Small

`wow_vocab_core_small.csv`

Essential fantasy/RPG vocabulary.

Best for:

- quick start
- first pass through high-value words
- compact flashcard decks
- players moving to an English client or English-speaking realm

### Core Medium

`wow_vocab_core_medium.csv`

Recommended vocabulary for reading fantasy/RPG/WoW English.

Best for:

- reading quest text
- understanding item names and descriptions
- following lore, dialogue, dungeon journal text, and worldbuilding
- learning both fantasy-register and story vocabulary

### Core Large

`wow_vocab_core_large.csv`

Broad vocabulary coverage for deeper reading and self-study.

Best for:

- deeper self-study
- building Anki decks
- linguistic analysis
- advanced fantasy/RPG reading
- custom learner tools

### Lemma Large

`wow_vocab_core_lemma_large.csv`

Lemma-level version of the large dictionary.

Inflected forms are grouped into one row when they share the same lemma.

Example:

```text
add
added
adds
```

become one entry:

```text
lemma: add
forms: add;adds;added
form_counts: add:83;adds:21;added:13
raw_count_total: 117
```

Use this file when you want to study base forms instead of treating every inflected form as a separate word.

### Word Families

`wow_vocab_families.csv`

Word-family grouping.

This file groups forms, derived forms, compound forms, related words, categories, and frequency metadata at a broader family level.

It is useful when a learner wants to study a semantic family together.

The workbook contains readable sheets for:

- Core Small
- Core Medium
- Core Large
- Lemma Large
- Families

Use the CSV or JSONL files when you need scripts, imports, or custom processing.

## What Makes This Different

This is not a generic English frequency list.

The dictionaries focus on words that matter in fantasy and RPG contexts, including:

- elevated, archaic, religious, and ritual vocabulary
- words used in items, spells, quests, dialogue, and lore
- word families and derived forms
- semantic categories instead of flat alphabetical lists
- frequency and source-diversity metadata
- language-neutral structure for different native-language learners

Examples:

- **hallow / hallowed / hallowing**
- **profane / profanity**
- **defile / defiled / defilement**
- **corrupt / corrupted / corruption**
- **dragon / drake / wyrm / whelp / brood**
- **oath / oathbound / sworn**
- **relic / sigil / rune / glyph**

## Categories

Words are grouped by semantic and genre categories, such as:

- Light / holiness / sacred places
- Darkness / profane / anti-sacred vocabulary
- Corruption / defilement / curses
- Death / undead / crypts
- Void / cosmic horror / Old Gods
- Dragons / draconic vocabulary
- Titans / order / machinery
- Magic / artifacts / runes
- Nature / primal forces
- Nobility / rule / power
- Law / oaths / exile / judgment
- War / betrayal / conflict
- Family / relationships / social life
- Travel / places / worldbuilding

## Word Families

The dictionaries are designed to preserve word families.

Instead of treating every form as an isolated word, related forms are grouped where possible:

```text
hallow
├─ hallowed
├─ hallowing
├─ related: holy, sacred, consecrate, sanctify
└─ opposed: profane, defile, desecrate
```

```text
defile
├─ defiled
├─ defiling
├─ defilement
├─ related: desecrate, taint, corrupt
└─ opposed: hallow, sanctify, consecrate
```

This lets learners choose whether to study only the headword first or learn the whole family at once.

## File Formats

Most dictionaries are provided in three formats:

- `.csv` - useful for scripts, imports, and data processing
- `.jsonl` - useful for programmatic tools and pipelines
- `.md` - readable Markdown preview

For office software, use:

- `wow_vocab_core_readable.xlsx`

## Common Fields

The public dictionaries use derived metadata fields such as:

- `word`
- `lemma`
- `headword`
- `word_family_id`
- `canonical_headword`
- `family_role`
- `forms`
- `derived_forms`
- `compound_forms`
- `categories`
- `register`
- `meaning_en_simple`
- `semantic_notes`
- `related_words`
- `opposites`
- `common_collocations`
- `raw_count_total`
- `document_frequency_total`
- `source_diversity`
- `source_tables`
- `form_counts`
- `core_score`
- `confidence`
- `needs_human_review`
- `review_reason`

## Who Is This For?

This vocabulary is useful if you:

- play RPGs or MMORPGs in English
- moved from a localized client to an English client
- can read basic English but struggle with fantasy/lore vocabulary
- want to understand item names, quest text, spell names, and dialogue more naturally
- build Anki decks or personal vocabulary systems
- study English through fantasy games

## What This Is Not

This is not:

- a beginner English course
- a translation of World of Warcraft text
- a replacement for official localization
- a corpus of Blizzard game text
- a weekly study plan

It is a structured vocabulary resource.

Learners can use it to build study plans, flashcards, reading lists, or language packs.

## Copyright Note

This repository does not redistribute World of Warcraft quest text, NPC dialogue, item descriptions, journal text, or other Blizzard-owned source text.

The public dictionaries contain derived vocabulary metadata only.

That metadata includes words, lemmas, categories, registers, frequency counts, word-family information, and simple English explanations.

World of Warcraft and related names are trademarks or registered trademarks of Blizzard Entertainment, Inc.

This project is unofficial and is not endorsed by or affiliated with Blizzard Entertainment.

## License

The dictionary metadata, formatting, spreadsheet workbook, and documentation in this artifact may be used under the **MIT License**, unless otherwise noted.

The underlying World of Warcraft game text and data files are not included in this public artifact and are not licensed here.

## Suggested GitHub About

```text
A curated fantasy/RPG English vocabulary dataset for learners who know basic English but struggle with words like hallowed, profane, defiled, sundered, attuned, wyrm, covenant, and oathbound.
```

## Suggested Topics

```text
fantasy
rpg
english-learning
vocabulary
world-of-warcraft
mmorpg
language-learning
corpus-analysis
word-frequency
word-families
```
