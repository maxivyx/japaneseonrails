# JapaneseOnRails
There's a finite amount of Japanese one can learn
---

### Core Principle

- Every element in the Japanese language is a node.
- Each node has a limited number of valid connections.
- You trace a word from its atomic form → function → use in real context.

### Node Building Blocks
*(Ordered from smallest to largest)*

1) **Glyph:** visual or phonetic symbol. Functionally an irreducible unit. 
   
	- Kana glyph - た、い、カ
	- Kanji glyph - 出、食、外
  
- Each glyph may:
  
	- Have a sound (kana) or multiple readings (kanji)
	- Appear in many words
	- Contain radicals (kanji)
  
- Properties:
  
	- Kana: purely phonetic (1:1 sound representation)
	- Kanji: semantic + phonetic load; multiple readings
	- Kanji may contain radicals (subcomponents)

- Connections:
  
	- Compose morphemes
	- Kanji glyphs used across many words with semantic drift
	- Serve as identity roots for recognition and orthographic tracing

2) **Morpheme:** smallest semantic unit -- not always a full word.

	- 見 = "see" (core meaning, appears in multiple words)
	- 〜たい = desire suffix
	- 〜なかった = negative-past suffix
  
- Morphemes combine to form words and inflections.
  
- Properties:
  
	- May require attachment or be free-standing
	- Responsible for grammatical function, tense, voice, etc.
	- Morphology base for inflection and grammar patterns

- Connections:

	- Combine to create words and functional patterns
	- Visible in inflectional endings and grammatical scaffolds

3) **Inflected Form:** temporary word shape based on conjugation, often unique to a grammar role.

	- 出た (past of 出る)
	- 食べられる (potential or passive of 食べる)

- Multiple may point to the same root.

- Properties:
  
	- Tied to context
	- Ambiguous in isolation

- Connections:

	- Maps back to one root word
	- Bridges into grammar patterns

4) **Word:** compound of glyphs and morphemes forming a distinct lexical item.

	- Kana/Kanji form
	- Part of speech
	- Conjugation class (godan, ichidan, etc.)
	- Dictionary meaning(s)
	- Register (formal/informal)

- Properties:

	- Has a fixed reading, core meaning, and part of speech
	- May have multiple definitions based on usage
	- Exists in dictionary form

- Connections: 

	- Generates inflected forms
	- Participates in grammar structures

5) **Functional Grammar Pattern:** syntactic structure involving one or more morphemes.

	- 〜てから
	- 〜ないで
	- 〜たことがある

- Control clause logic, tense, intention, condition, etc.

- Properties:

	- Define tense, cause/effect, hypotheticals, etc.
	- Often fixed expressions with rigid form
	- JLPT-categorized patterns (N5 to N1)

- Connections:

	- Anchor words and forms into clauses
	- Realized in complete sentences
	- Bind verbs to consequence logic

6) **Sentence:** a structured assembly of all above.

	- Glyphs
	- Morphemes
	- Inflected Forms
	- Words
	- Grammar Patterns

- Properties:

	- Built from words, inflected forms, and grammar
	- Minimal unit for conveying complete meaning (includes phrases)
	- First place where intent, tone, and role clarity emerge
	- Foundation for large composite data, such as paragraphs, essays, articles, etc.

- Connections:

	- Words ↔ Grammar patterns ↔ Morphemes
	- Every sentence logs what was used, how it was used, and in what structure

7) **Context/Scene:** macro unit -- multiple sentences tied to one situation, tone, or emotional arc.

- Properties:

	- Contains tone, emotion, or temporal continuity
	- May show formality, dialect or speaker personality
	- Useful for exposure and immersion

- Connections: 

	- Groups multiple sentences using common patterns, vocabulary
	- Can be used to reinforce theme or situation-specific usage

### Language Modules

- [[Structure]]
- [[Radicals]]
- [[Writing-Systems]]
- [[Global-Exceptions]]
- [[Loanwords]]
- [[Counter-Systems]]
- [[Word-Types]]
- [[Compound-Verbs]]
- [[Kanji-Readings]]
- [[Inflection-Systems]]
- [[Role-Based-Speech]]
- [[Pitch-Accent]]
- [[Grammar-Patterns]]
- [[Synonym-Network]]
- [[Particles]]
- [[Discourse-Particles]]
- [[Contraction-Logic]]
- [[Onomatopoeia-System]]
- [[Phonetic-Deviation]]
- [[Politeness System]]
- [[Phrases-and-Idioms]]
- [[Sentence-Tagging]]
- [[Context-Tracking]]

### Software Modules 
##### System Foundations

- [[App-Architecture]]  
  > Core overview. Node-based architecture. Modular boundaries. Vector-space model of Japanese.
  
- [[Data-Model]]  
  > Entity definitions. Fields. Relationships. Node types: Word, Form, Sentence, Grammar, Morpheme.

- [[Vector-Space-Logic]]  
  > How relationships are computed. Finite connection paths. Neighborhood logic. Distance scoring.

---
##### Learning Engine

- [[Node-Tracking]]  
  > Mastery logs. Exposure logs. Memory weight accrual. Time decay functions.

- [[Drill-Engine]]  
  > Flashcard as node-surface. Customizable drill loops. Context-forcing logic. Sentence-first toggles.

- [[Conjugation-Mapper]]  
  > Canonical verb forms. Class-specific inflections. Reverse-lookup capability.

- [[Grammar-Linker]]  
  > Pattern traceability engine. Connects grammar units to real contexts. Reverse-linked discovery.

---
##### Interface

- [[UI-Logic]]  
  > Navigation flow. Hover → expand → trace drill. Tap to surface connections.

- [[Flashcard-Presenter]]  
  > One node → all connections → condensed, readable surface. Includes:
    - Form
    - Meaning
    - Pitch
    - Connected sentences
    - Connected grammar
    - Mastery level
    - Custom tag color overlays

- [[Color-System]]  
  > Visual logic of memory cues. Custom tag + color combo system. Tracks:
    - Register
    - Difficulty
    - Formality
    - Status (mastered, seen, new)
